TOP=..

include $(TOP)/configure/CONFIG

CFG += CONFIG_HPSTPR

TARGETS = $(CONFIG_TARGETS)
CONFIGS += $(subst ../,,$(wildcard $(CONFIG_INSTALLS)))

include $(TOP)/configure/RULES
