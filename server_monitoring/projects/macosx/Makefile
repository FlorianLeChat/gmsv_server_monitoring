# GNU Make workspace makefile autogenerated by Premake

ifndef config
  config=debug
endif

ifndef verbose
  SILENT = @
endif

ifeq ($(config),debug)
  gmsv_server_monitoring_config = debug
endif
ifeq ($(config),release)
  gmsv_server_monitoring_config = release
endif

PROJECTS := gmsv_server_monitoring

.PHONY: all clean help $(PROJECTS) 

all: $(PROJECTS)

gmsv_server_monitoring:
ifneq (,$(gmsv_server_monitoring_config))
	@echo "==== Building gmsv_server_monitoring ($(gmsv_server_monitoring_config)) ===="
	@${MAKE} --no-print-directory -C . -f gmsv_server_monitoring.make config=$(gmsv_server_monitoring_config)
endif

clean:
	@${MAKE} --no-print-directory -C . -f gmsv_server_monitoring.make clean

help:
	@echo "Usage: make [config=name] [target]"
	@echo ""
	@echo "CONFIGURATIONS:"
	@echo "  debug"
	@echo "  release"
	@echo ""
	@echo "TARGETS:"
	@echo "   all (default)"
	@echo "   clean"
	@echo "   gmsv_server_monitoring"
	@echo ""
	@echo "For more information, see https://github.com/premake/premake-core/wiki"