ifeq ($(clienttype),full)
	source=client_full.c client_common.c commands.c util.c
else
	source=client_light.c client_common.c commands.c util.c
endif
root-rel=../
dir-name=client

include ../Rules
