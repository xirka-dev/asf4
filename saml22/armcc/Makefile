
################################################################################
# Automatically-generated file. Do not edit!
################################################################################

ifdef SystemRoot
	SHELL = cmd.exe
	MK_DIR = mkdir
else
	ifeq ($(shell uname), Linux)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), CYGWIN)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), MINGW32)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), MINGW64)
		MK_DIR = mkdir -p
	endif
endif

# List the subdirectories for creating object files
SUB_DIRS +=  \
 \
hpl/adc \
usb/class/cdc/device \
examples \
hpl/systick \
hpl/oscctrl \
hpl/tc \
hpl/osc32kctrl \
usb \
hpl/dmac \
hal/src \
hpl/eic \
hpl/wdt \
hpl/rtc \
hpl/trng \
hpl/usb \
armcc/Device/SAML22/Source \
hpl/mclk \
hpl/slcd \
hpl/gclk \
qtouch \
hal/utils/src \
usb/device \
hpl/pm \
usb/class/msc/device \
hpl/pac \
armcc/Device/SAML22/Source/ARM \
hpl/sercom \
hpl/nvmctrl \
hpl/core

# List the object files
OBJS +=  \
hal/src/hal_io.o \
hpl/systick/hpl_systick.o \
qtouch/touch.o \
hpl/wdt/hpl_wdt.o \
hal/utils/src/utils_event.o \
usb/usb_protocol.o \
hpl/eic/hpl_eic.o \
hal/src/hal_pac.o \
usb/class/cdc/device/cdcdf_acm.o \
hpl/nvmctrl/hpl_nvmctrl.o \
hal/src/hal_slcd_sync.o \
hal/src/hal_spi_m_sync.o \
usb_start.o \
hal/src/hal_timer.o \
hal/src/hal_pwm.o \
hpl/usb/hpl_usb.o \
hal/src/hal_i2c_m_sync.o \
hal/src/hal_delay.o \
hpl/oscctrl/hpl_oscctrl.o \
hpl/core/hpl_init.o \
hal/src/hal_wdt.o \
hpl/core/hpl_core_m0plus_base.o \
hal/utils/src/utils_assert.o \
hpl/pac/hpl_pac.o \
hpl/pm/hpl_pm.o \
hal/src/hal_rand_sync.o \
hpl/trng/hpl_trng.o \
hal/src/hal_usart_sync.o \
hpl/mclk/hpl_mclk.o \
hpl/sercom/hpl_sercom.o \
hpl/gclk/hpl_gclk.o \
hal/src/hal_flash.o \
hal/src/hal_init.o \
hal/src/hal_usb_device.o \
main.o \
hal/utils/src/utils_list.o \
hpl/osc32kctrl/hpl_osc32kctrl.o \
hpl/rtc/hpl_rtc.o \
examples/driver_examples.o \
driver_init.o \
usb/class/msc/device/mscdf.o \
hal/src/hal_adc_sync.o \
hpl/slcd/hpl_slcd.o \
hal/src/hal_ext_irq.o \
armcc/Device/SAML22/Source/system_saml22.o \
hal/src/hal_gpio.o \
examples/touch_example.o \
hal/src/hal_sleep.o \
hpl/dmac/hpl_dmac.o \
atmel_start.o \
usb/device/usbdc.o \
hpl/tc/hpl_tc.o \
armcc/Device/SAML22/Source/ARM/startup_SAML22.o \
hal/src/hal_atomic.o \
hpl/adc/hpl_adc.o

OBJS_AS_ARGS +=  \
"hal/src/hal_io.o" \
"hpl/systick/hpl_systick.o" \
"qtouch/touch.o" \
"hpl/wdt/hpl_wdt.o" \
"hal/utils/src/utils_event.o" \
"usb/usb_protocol.o" \
"hpl/eic/hpl_eic.o" \
"hal/src/hal_pac.o" \
"usb/class/cdc/device/cdcdf_acm.o" \
"hpl/nvmctrl/hpl_nvmctrl.o" \
"hal/src/hal_slcd_sync.o" \
"hal/src/hal_spi_m_sync.o" \
"usb_start.o" \
"hal/src/hal_timer.o" \
"hal/src/hal_pwm.o" \
"hpl/usb/hpl_usb.o" \
"hal/src/hal_i2c_m_sync.o" \
"hal/src/hal_delay.o" \
"hpl/oscctrl/hpl_oscctrl.o" \
"hpl/core/hpl_init.o" \
"hal/src/hal_wdt.o" \
"hpl/core/hpl_core_m0plus_base.o" \
"hal/utils/src/utils_assert.o" \
"hpl/pac/hpl_pac.o" \
"hpl/pm/hpl_pm.o" \
"hal/src/hal_rand_sync.o" \
"hpl/trng/hpl_trng.o" \
"hal/src/hal_usart_sync.o" \
"hpl/mclk/hpl_mclk.o" \
"hpl/sercom/hpl_sercom.o" \
"hpl/gclk/hpl_gclk.o" \
"hal/src/hal_flash.o" \
"hal/src/hal_init.o" \
"hal/src/hal_usb_device.o" \
"main.o" \
"hal/utils/src/utils_list.o" \
"hpl/osc32kctrl/hpl_osc32kctrl.o" \
"hpl/rtc/hpl_rtc.o" \
"examples/driver_examples.o" \
"driver_init.o" \
"usb/class/msc/device/mscdf.o" \
"hal/src/hal_adc_sync.o" \
"hpl/slcd/hpl_slcd.o" \
"hal/src/hal_ext_irq.o" \
"armcc/Device/SAML22/Source/system_saml22.o" \
"hal/src/hal_gpio.o" \
"examples/touch_example.o" \
"hal/src/hal_sleep.o" \
"hpl/dmac/hpl_dmac.o" \
"atmel_start.o" \
"usb/device/usbdc.o" \
"hpl/tc/hpl_tc.o" \
"armcc/Device/SAML22/Source/ARM/startup_SAML22.o" \
"hal/src/hal_atomic.o" \
"hpl/adc/hpl_adc.o"

# List the dependency files
DEPS := $(OBJS:%.o=%.d)

DEPS_AS_ARGS +=  \
"usb/usb_protocol.d" \
"qtouch/touch.d" \
"hpl/wdt/hpl_wdt.d" \
"examples/touch_example.d" \
"hal/src/hal_io.d" \
"hpl/systick/hpl_systick.d" \
"hal/src/hal_pac.d" \
"hpl/eic/hpl_eic.d" \
"usb/class/cdc/device/cdcdf_acm.d" \
"hal/src/hal_i2c_m_sync.d" \
"hpl/usb/hpl_usb.d" \
"hal/utils/src/utils_event.d" \
"usb/class/msc/device/mscdf.d" \
"hpl/nvmctrl/hpl_nvmctrl.d" \
"hal/src/hal_pwm.d" \
"hal/src/hal_timer.d" \
"hal/src/hal_spi_m_sync.d" \
"hpl/core/hpl_core_m0plus_base.d" \
"hal/src/hal_wdt.d" \
"hpl/dmac/hpl_dmac.d" \
"hal/utils/src/utils_assert.d" \
"hal/src/hal_delay.d" \
"hpl/core/hpl_init.d" \
"hpl/pm/hpl_pm.d" \
"hal/src/hal_flash.d" \
"hpl/gclk/hpl_gclk.d" \
"hal/src/hal_usb_device.d" \
"hpl/pac/hpl_pac.d" \
"hal/src/hal_init.d" \
"hal/src/hal_usart_sync.d" \
"hpl/trng/hpl_trng.d" \
"hal/src/hal_rand_sync.d" \
"hpl/mclk/hpl_mclk.d" \
"driver_init.d" \
"usb_start.d" \
"hpl/slcd/hpl_slcd.d" \
"hal/src/hal_adc_sync.d" \
"hpl/osc32kctrl/hpl_osc32kctrl.d" \
"main.d" \
"examples/driver_examples.d" \
"hpl/rtc/hpl_rtc.d" \
"hal/src/hal_slcd_sync.d" \
"hal/utils/src/utils_list.d" \
"hal/src/hal_sleep.d" \
"armcc/Device/SAML22/Source/system_saml22.d" \
"hpl/sercom/hpl_sercom.d" \
"hal/src/hal_gpio.d" \
"atmel_start.d" \
"hal/src/hal_atomic.d" \
"armcc/Device/SAML22/Source/ARM/startup_SAML22.d" \
"hpl/tc/hpl_tc.d" \
"usb/device/usbdc.d" \
"hpl/oscctrl/hpl_oscctrl.d" \
"hpl/adc/hpl_adc.d" \
"hal/src/hal_ext_irq.d"

OUTPUT_FILE_NAME :=AtmelStart
QUOTE := "
OUTPUT_FILE_PATH +=$(OUTPUT_FILE_NAME).elf
OUTPUT_FILE_PATH_AS_ARGS +=$(OUTPUT_FILE_NAME).elf

vpath %.c ../
vpath %.s ../
vpath %.S ../

# All Target
all: $(SUB_DIRS) $(OUTPUT_FILE_PATH)

# Linker target

$(OUTPUT_FILE_PATH): $(OBJS)
	@echo Building target: $@
	@echo Invoking: ARMCC Linker
	$(QUOTE)armlink$(QUOTE) --ro-base 0x00000000 --entry 0x00000000 --rw-base 0x20000000 --entry Reset_Handler --first __Vectors \
--strict --summary_stderr --info summarysizes --map --xref --callgraph --symbols \
--info sizes --info totals --info unused --info veneers --list $(OUTPUT_FILE_NAME).map \
-o $(OUTPUT_FILE_NAME).elf --cpu Cortex-M0+ \
$(OBJS_AS_ARGS)

	@echo Finished building target: $@

# Compiler target(s)




%.o: %.c
	@echo Building file: $<
	@echo ARMCC Compiler
	$(QUOTE)armcc$(QUOTE) --c99 -c -DDEBUG -O1 -g --apcs=interwork --split_sections --cpu Cortex-M0+ -D__SAML22J18A__ \
-I"../" -I"../config" -I"../examples" -I"../hal/include" -I"../hal/utils/include" -I"../hpl/adc" -I"../hpl/core" -I"../hpl/dmac" -I"../hpl/eic" -I"../hpl/gclk" -I"../hpl/mclk" -I"../hpl/nvmctrl" -I"../hpl/osc32kctrl" -I"../hpl/oscctrl" -I"../hpl/pac" -I"../hpl/pm" -I"../hpl/port" -I"../hpl/rtc" -I"../hpl/sercom" -I"../hpl/slcd" -I"../hpl/systick" -I"../hpl/tc" -I"../hpl/trng" -I"../hpl/usb" -I"../hpl/wdt" -I"../hri" -I"../." -I"../documentation" -I"../examples" -I"../qtouch" -I"../qtouch/include" -I"../" -I"../config" -I"../usb" -I"../usb/class/cdc" -I"../usb/class/cdc/device" -I"../usb/class/msc" -I"../usb/class/msc/device" -I"../usb/device" -I"../" -I"../CMSIS/Core/Include" -I"../include"  \
--depend "$@"  -o "$@" "$<"

	@echo Finished building: $<

%.o: %.s
	@echo Building file: $<
	@echo ARMCC Assembler
	$(QUOTE)armasm$(QUOTE) -g --apcs=interwork --cpu Cortex-M0+ --pd "D__SAML22J18A__ SETA 1" \
-I"../" -I"../config" -I"../examples" -I"../hal/include" -I"../hal/utils/include" -I"../hpl/adc" -I"../hpl/core" -I"../hpl/dmac" -I"../hpl/eic" -I"../hpl/gclk" -I"../hpl/mclk" -I"../hpl/nvmctrl" -I"../hpl/osc32kctrl" -I"../hpl/oscctrl" -I"../hpl/pac" -I"../hpl/pm" -I"../hpl/port" -I"../hpl/rtc" -I"../hpl/sercom" -I"../hpl/slcd" -I"../hpl/systick" -I"../hpl/tc" -I"../hpl/trng" -I"../hpl/usb" -I"../hpl/wdt" -I"../hri" -I"../." -I"../documentation" -I"../examples" -I"../qtouch" -I"../qtouch/include" -I"../" -I"../config" -I"../usb" -I"../usb/class/cdc" -I"../usb/class/cdc/device" -I"../usb/class/msc" -I"../usb/class/msc/device" -I"../usb/device" -I"../" -I"../CMSIS/Core/Include" -I"../include"  \
--depend "$(@:%.o=%.d)" -o "$@" "$<"

	@echo Finished building: $<

%.o: %.S
	@echo Building file: $<
	@echo ARMCC Preprocessing Assembler
	$(QUOTE)armcc$(QUOTE) --c99 -c -DDEBUG -O1 -g --apcs=interwork --split_sections --cpu Cortex-M0+ -D__SAML22J18A__ \
-I"../" -I"../config" -I"../examples" -I"../hal/include" -I"../hal/utils/include" -I"../hpl/adc" -I"../hpl/core" -I"../hpl/dmac" -I"../hpl/eic" -I"../hpl/gclk" -I"../hpl/mclk" -I"../hpl/nvmctrl" -I"../hpl/osc32kctrl" -I"../hpl/oscctrl" -I"../hpl/pac" -I"../hpl/pm" -I"../hpl/port" -I"../hpl/rtc" -I"../hpl/sercom" -I"../hpl/slcd" -I"../hpl/systick" -I"../hpl/tc" -I"../hpl/trng" -I"../hpl/usb" -I"../hpl/wdt" -I"../hri" -I"../." -I"../documentation" -I"../examples" -I"../qtouch" -I"../qtouch/include" -I"../" -I"../config" -I"../usb" -I"../usb/class/cdc" -I"../usb/class/cdc/device" -I"../usb/class/msc" -I"../usb/class/msc/device" -I"../usb/device" -I"../" -I"../CMSIS/Core/Include" -I"../include"  \
--depend "$@"  -o "$@" "$<"

	@echo Finished building: $<

# Detect changes in the dependent files and recompile the respective object files.
ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(DEPS)),)
-include $(DEPS)
endif
endif

$(SUB_DIRS):
	$(MK_DIR) "$@"

clean:
	rm -f $(OBJS_AS_ARGS)
	rm -f $(OUTPUT_FILE_PATH)
	rm -f $(DEPS_AS_ARGS)
	rm -f $(OUTPUT_FILE_NAME).map $(OUTPUT_FILE_NAME).elf
