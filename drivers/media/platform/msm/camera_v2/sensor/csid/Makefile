CFLAGS_msm_csid.o := -fno-graphite -fno-graphite-identity -fno-loop-flatten -fno-tree-loop-linear -fno-loop-interchange -fno-loop-strip-mine -fno-loop-block -fno-loop-nest-optimize -fno-loop-parallelize-all -ftree-parallelize-loops=0 -fno-openmp -fno-fast-math -fno-strict-aliasing -fno-unsafe-math-optimizations

ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
obj-$(CONFIG_MSM_CSID) += msm_csid.o
