################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccs1210/ccs/tools/compiler/ti-cgt-msp430_21.6.0.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./Common/hal_UCS.obj" \
"./Common/hal_pmm.obj" \
"./Common/hal_tlv.obj" \
"./SRC/ADS1x9x.obj" \
"./SRC/ADS1x9x_ECG_Processing.obj" \
"./SRC/ADS1x9x_Nand_Flash.obj" \
"./SRC/ADS1x9x_Nand_LLD.obj" \
"./SRC/ADS1x9x_RESP_Processing.obj" \
"./SRC/ADS1x9x_USB_Communication.obj" \
"./SRC/ADS1x9x_main.obj" \
"./SRC/USB_constructs.obj" \
"./USB_CDC_API/UsbCdc.obj" \
"./USB_Common/UsbIsr.obj" \
"./USB_Common/descriptors.obj" \
"./USB_Common/dma.obj" \
"./USB_Common/usb.obj" \
"./USB_Common/usb_eventHandling.obj" \
"../lnk_msp430f5529.cmd" \
$(GEN_CMDS__FLAG) \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include Common/subdir_vars.mk
-include SRC/subdir_vars.mk
-include USB_CDC_API/subdir_vars.mk
-include USB_Common/subdir_vars.mk
-include subdir_rules.mk
-include Common/subdir_rules.mk
-include SRC/subdir_rules.mk
-include USB_CDC_API/subdir_rules.mk
-include USB_Common/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
ADS1x9x_ECG_Recorder_FW.out \

EXE_OUTPUTS__QUOTED += \
"ADS1x9x_ECG_Recorder_FW.out" \


# All Target
all: ADS1x9x_ECG_Recorder_FW.out

# Tool invocations
ADS1x9x_ECG_Recorder_FW.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: "$@"'
	@echo 'Invoking: MSP430 Linker'
	"C:/ti/ccs1210/ccs/tools/compiler/ti-cgt-msp430_21.6.0.LTS/bin/cl430" --silicon_version=mspx -g -O2 --define=__MSP430F5529__ --define=__MSP430F5529 --diag_warning=225 --printf_support=minimal -z -m"ADS1292R_ECG_Recorder.map" --stack_size=160 --heap_size=160 --use_hw_mpy=F5 --warn_sections -i"C:/ti/ccs1210/ccs/ccs_base/msp430/include" -i"C:/ti/ccs1210/ccs/msp430/include" -i"C:/ti/ccs1210/ccs/tools/compiler/ti-cgt-msp430_21.6.0.LTS/lib" -i"C:/ti/ccs1210/ccs/tools/compiler/ti-cgt-msp430_21.6.0.LTS/include" --reread_libs --xml_link_info="ADS1x9x_ECG_Recorder_FW_linkInfo.xml" --rom_model -o "ADS1x9x_ECG_Recorder_FW.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)
	-$(RM) "Common\hal_UCS.obj" "Common\hal_pmm.obj" "Common\hal_tlv.obj" "SRC\ADS1x9x.obj" "SRC\ADS1x9x_ECG_Processing.obj" "SRC\ADS1x9x_Nand_Flash.obj" "SRC\ADS1x9x_Nand_LLD.obj" "SRC\ADS1x9x_RESP_Processing.obj" "SRC\ADS1x9x_USB_Communication.obj" "SRC\ADS1x9x_main.obj" "SRC\USB_constructs.obj" "USB_CDC_API\UsbCdc.obj" "USB_Common\UsbIsr.obj" "USB_Common\descriptors.obj" "USB_Common\dma.obj" "USB_Common\usb.obj" "USB_Common\usb_eventHandling.obj" 
	-$(RM) "Common\hal_UCS.d" "Common\hal_pmm.d" "Common\hal_tlv.d" "SRC\ADS1x9x.d" "SRC\ADS1x9x_ECG_Processing.d" "SRC\ADS1x9x_Nand_Flash.d" "SRC\ADS1x9x_Nand_LLD.d" "SRC\ADS1x9x_RESP_Processing.d" "SRC\ADS1x9x_USB_Communication.d" "SRC\ADS1x9x_main.d" "SRC\USB_constructs.d" "USB_CDC_API\UsbCdc.d" "USB_Common\UsbIsr.d" "USB_Common\descriptors.d" "USB_Common\dma.d" "USB_Common\usb.d" "USB_Common\usb_eventHandling.d" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-@echo 'Create flash image: TI-TXT'
	-"C:/ti/ccs1210/ccs/tools/compiler/ti-cgt-msp430_21.6.0.LTS/bin/hex430.exe" --ti_txt "ADS1x9x_ECG_Recorder_FW.out" -o "ADS1x9x_ECG_Recorder_FW.txt" -order MS -romwidth 16
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

