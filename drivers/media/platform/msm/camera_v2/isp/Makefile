CFLAGS_msm_isp_axi_util.o := -fno-graphite -fno-graphite-identity -fno-loop-flatten -fno-tree-loop-linear -fno-loop-interchange -fno-loop-strip-mine -fno-loop-block -fno-loop-nest-optimize -fno-loop-parallelize-all -ftree-parallelize-loops=0 -fno-openmp -fno-fast-math -fno-strict-aliasing -fno-unsafe-math-optimizations
CFLAGS_msm_isp_stats_util.o := -fno-graphite -fno-graphite-identity -fno-loop-flatten -fno-tree-loop-linear -fno-loop-interchange -fno-loop-strip-mine -fno-loop-block -fno-loop-nest-optimize -fno-loop-parallelize-all -ftree-parallelize-loops=0 -fno-openmp -fno-fast-math -fno-strict-aliasing -fno-unsafe-math-optimizations

ccflags-y += -Idrivers/media/platform/msm/camera_v2
ccflags-y += -Idrivers/media/platform/msm/camera_v2/sensor/io
ccflags-y += -Idrivers/media/platform/msm/camera_v2/common/
obj-$(CONFIG_MSMB_CAMERA) += msm_buf_mgr.o msm_isp_util.o msm_isp_axi_util.o msm_isp_stats_util.o
obj-$(CONFIG_MSMB_CAMERA) += msm_isp48.o msm_isp47.o msm_isp46.o msm_isp44.o msm_isp40.o msm_isp.o
