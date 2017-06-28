#
# Makefile for kernel slimbus framework.
#
CFLAGS_slim-msm-ngd.o := -fno-graphite -fno-graphite-identity -fno-loop-flatten -fno-tree-loop-linear -fno-loop-interchange -fno-loop-strip-mine -fno-loop-block -fno-loop-nest-optimize -fno-loop-parallelize-all -ftree-parallelize-loops=0 -fno-openmp -fno-fast-math -fno-strict-aliasing -fno-unsafe-math-optimizations

obj-$(CONFIG_SLIMBUS)			+= slimbus.o
obj-$(CONFIG_SLIMBUS_MSM_CTRL)		+= slim-msm.o slim-msm-ctrl.o
obj-$(CONFIG_SLIMBUS_MSM_NGD)		+= slim-msm.o slim-msm-ngd.o
