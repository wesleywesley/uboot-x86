dtb-y += chromebook_link.dtb \
	chromebox_panther.dtb \
	crownbay.dtb \
	galileo.dtb \
	minnowmax.dtb \
	qemu-x86.dtb

targets += $(dtb-y)

DTC_FLAGS += -R 4 -p 0x1000

PHONY += dtbs
dtbs: $(addprefix $(obj)/, $(dtb-y))
	@:

clean-files := *.dtb
