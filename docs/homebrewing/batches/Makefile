DIRS = graphs \
	batch_1 \
	batch_2 \
	batch_3 \
	batch_4 \
	batch_5 \
	batch_6 \
	batch_7 \
	batch_8 \
	batch_9 \
	batch_10 \
	batch_11 \
	batch_12 \
	batch_13 \
	batch_14 \
	batch_15 \
	batch_16 \
	batch_17 \
	batch_18 \
	batch_19 \
	batch_20 \
	batch_21 \
	batch_22 \
	batch_23 \
	batch_24 \
	batch_25 \
	batch_26 \
	batch_27 \
	batch_28 \
	batch_29 \
	batch_30 \
	batch_31 \
	batch_32 \
	batch_33 \
	batch_34 \
	batch_35 \
	batch_36 \
	batch_37 \
	batch_38 \
	batch_39 \
	batch_40 \
	batch_41 \
	batch_42 \
	batch_43

.DEFAULT_GOAL := all

all:
	target=`echo $@ | sed s/-recursive//`; \
	list='$(DIRS)'; for subdir in $$list; do \
		echo "Making $$target in $$subdir"; \
		cd $$subdir; \
		make -B all; \
		cd ..; \
	done;
