OBJ_FILES := dtbtool.o
CFLAGS := -static -Os -Wall
TOOL_NAME := dtbTool

all: ${TOOL_NAME}

${TOOL_NAME}: $(OBJ_FILES)
	$(CC) $(CFLAGS) -o $@ $^
	strip --strip-all $@

clean:
	rm -f $(OBJ_FILES) ${TOOL_NAME}

