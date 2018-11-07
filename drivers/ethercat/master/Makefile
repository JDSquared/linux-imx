obj-$(CONFIG_ETHERCAT) += ec_master.o

ec_master-y := \
	cdev.o \
	coe_emerg_ring.o \
	datagram.o \
	datagram_pair.o \
	device.o \
	domain.o \
	eoe_request.o \
	fmmu_config.o \
	foe_request.o \
	fsm_change.o \
	fsm_coe.o \
	fsm_eoe.o \
	fsm_foe.o \
	fsm_master.o \
	fsm_pdo.o \
	fsm_pdo_entry.o \
	fsm_sii.o \
	fsm_slave.o \
	fsm_slave_config.o \
	fsm_slave_scan.o \
	fsm_soe.o \
	ioctl.o \
	mailbox.o \
	master.o \
	module.o \
	pdo.o \
	pdo_entry.o \
	pdo_list.o \
	reg_request.o \
	sdo.o \
	sdo_entry.o \
	sdo_request.o \
	slave.o \
	slave_config.o \
	soe_errors.o \
	soe_request.o \
	sync.o \
	sync_config.o \
	voe_handler.o

ec_master-$(CONFIG_ETHERCAT_EOE) += ethernet.o
ccflags-$(CONFIG_ETHERCAT_EOE) += -DEC_EOE

ec_master-$(CONFIG_ETHERCAT_DEBUG_IF) += debug.o
ccflags-$(CONFIG_ETHERCAT_DEBUG_IF) += -DEC_DEBUG_IF

ccflags-$(CONFIG_ETHERCAT_HRTIMER) += -DEC_USE_HRTIMER
