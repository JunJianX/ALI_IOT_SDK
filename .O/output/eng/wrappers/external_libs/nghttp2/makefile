MODULE_NAME := output/eng/wrappers/external_libs/nghttp2
ALL_SUB_DIRS := certs external_libs/mbedtls external_libs/nghttp2 output/eng/wrappers/external_libs/mbedtls output/eng/wrappers/external_libs/nghttp2 src/atm src/coap src/dev_bind src/dev_model src/dev_reset src/dev_sign src/dynamic_register src/http src/http2 src/infra src/mqtt src/ota src/wifi_provision wrappers
AR := ar
CC := gcc
CFLAGS := --coverage -DCONFIG_MBEDTLS_DEBUG_LEVEL=0 -DCONFIG_MQTT_RX_MAXLEN=5000 -DDEVICE_MODEL_CLASSIC -DDEV_SIGN -DFORCE_SSL_VERIFY -DINFRA_COMPAT -DINFRA_LIST -DINFRA_LOG -DINFRA_LOG_ALL_MUTED -DINFRA_LOG_MUTE_CRT -DINFRA_LOG_MUTE_DBG -DINFRA_LOG_MUTE_ERR -DINFRA_LOG_MUTE_FLW -DINFRA_LOG_MUTE_INF -DINFRA_LOG_MUTE_WRN -DINFRA_LOG_NETWORK_PAYLOAD -DINFRA_NET -DINFRA_REPORT -DINFRA_SHA256 -DINFRA_STRING -DINFRA_TIMER -DMQTT_COMM_ENABLED -DMQTT_DEFAULT_IMPL -DMQTT_DIRECT -DPLATFORM_HAS_DYNMEM -DPLATFORM_HAS_STDINT -DSDK_TEAM_TEST -DWITH_MEM_STATS=0 -DWITH_MEM_STATS_PER_MODULE=0 -DWITH_MQTT_DYN_BUF=1 -DWITH_MQTT_JSON_FLOW=1 -DWITH_MQTT_SUB_SHORTCUT=1 -DWITH_MQTT_ZIP_TOPIC=1 -D_PLATFORM_IS_LINUX_ -D__UBUNTU_SDK_DEMO__ -Iwrappers -Os -Wall -Wdeclaration-after-statement -Werror -Wno-unused -ansi -g3 -rdynamic
COMP_LIB := libiot_sdk.a
COMP_LIB_COMPONENTS := src/dev_sign src/infra src/mqtt
CONFIG_VENDOR := ubuntu
CROSS_CANDIDATES := AR CC CXX LD OBJCOPY STRIP
CROSS_PREFIX := 
CXX := g++
EXPORT_DIR := 
IMPORT_DIR := tools/prebuilt
INSTALL_DIR := /home/xu/c-sdk-v3.0.1/.O/usr
INSTALL_LIB_DIR := /home/xu/c-sdk-v3.0.1/.O/usr/lib
KERNEL_DIR := 
LD := ld
LDFLAGS := -lpthread -lrt
MAKE_ENV_VARS := 
NOEXEC_CMAKE_DIRS := 
OBJCOPY := objcopy
PACKAGE_DIR := /home/xu/c-sdk-v3.0.1/packages
RULE_DIR := /home/xu/c-sdk-v3.0.1/tools/build-rules
STRIP := strip
SYSROOT_INC := /home/xu/c-sdk-v3.0.1/.O/usr/include
TOP_DIR := /home/xu/c-sdk-v3.0.1
WIN32_CMAKE_SKIP := 
COMP_LIB_FILES :=  libiot_infra.a  libiot_sign.a  libiot_mqtt.a

include $(RULE_DIR)/settings.mk
include $(CONFIG_TPL)

all:

LIBA_TARGET := libiot_nghttp2.a
HDR_REFS    += src/infra

env:
	@echo ""
	@printf -- "-----------------------------------------------------------------\n"
	@$(foreach var,$(SHOW_ENV_VARS),$(call Dump_Var,$(var)))
	@printf -- "-----------------------------------------------------------------\n"
	@echo ""

include $(RULE_DIR)/rules.mk
