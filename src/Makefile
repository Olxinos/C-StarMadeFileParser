################################################################################
# Local sample Makefile template.                                              #
#                                                                              #
# This file relies on the previous definition of the following variables:      #
# - ROOT_PATH : the path to the repository's root (either relative or          #
#               absolute)                                                      #
################################################################################

################################################################################
# internal variables                                                           #
################################################################################

ROOT_PATH := ..

#default target
all:

################################################################################
# Rules                                                                        #
################################################################################

include $(ROOT_PATH)/tools/build/compiler_options.mk
include ./rules.mk

################################################################################
# Targets                                                                #
################################################################################

.PHONY: all dynamic static clean

all: $(TARGETS)
dynamic: $(DYNLIB)
static: $(STATLIB)

clean:
	rm -rf $(CLEAN_TARGETS)