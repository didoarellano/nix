makefiles = local.mk

GLOBAL_CXXFLAGS += -g -Wall

-include Makefile.config

OPTIMIZE = 1

ifeq ($(OPTIMIZE), 1)
  GLOBAL_CFLAGS += -O3
  GLOBAL_CXXFLAGS += -O3
endif

include mk/lib.mk
