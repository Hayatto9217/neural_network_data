# Ymir: The Type-1 Hypervisor.v1.1.1
Zig言語によっての定理

# 本シリーズにおける主な参考文献は Intel® 64 and IA-32 Architectures Software Developer Manuals を参照しています。
https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html


### sysctl -a | grep hw.optional
hw.optional.arm.FEAT_FlagM: 1
hw.optional.arm.FEAT_FlagM2: 1
hw.optional.arm.FEAT_FHM: 1
hw.optional.arm.FEAT_DotProd: 1
hw.optional.arm.FEAT_SHA3: 1
hw.optional.arm.FEAT_RDM: 1
hw.optional.arm.FEAT_LSE: 1
hw.optional.arm.FEAT_SHA256: 1
hw.optional.arm.FEAT_SHA512: 1
hw.optional.arm.FEAT_SHA1: 1
hw.optional.arm.FEAT_AES: 1
hw.optional.arm.FEAT_PMULL: 1
hw.optional.arm.FEAT_SPECRES: 0
hw.optional.arm.FEAT_SB: 1
hw.optional.arm.FEAT_FRINTTS: 1
hw.optional.arm.FEAT_LRCPC: 1
hw.optional.arm.FEAT_LRCPC2: 1
hw.optional.arm.FEAT_FCMA: 1
hw.optional.arm.FEAT_JSCVT: 1
hw.optional.arm.FEAT_PAuth: 1
hw.optional.arm.FEAT_PAuth2: 1
hw.optional.arm.FEAT_FPAC: 1
hw.optional.arm.FEAT_DPB: 1
hw.optional.arm.FEAT_DPB2: 1
hw.optional.arm.FEAT_BF16: 1
hw.optional.arm.FEAT_I8MM: 1
hw.optional.arm.FEAT_WFxT: 0
hw.optional.arm.FEAT_RPRES: 1
hw.optional.arm.FEAT_ECV: 1
hw.optional.arm.FEAT_AFP: 1
hw.optional.arm.FEAT_LSE2: 1
hw.optional.arm.FEAT_CSV2: 1
hw.optional.arm.FEAT_CSV3: 1
hw.optional.arm.FEAT_DIT: 1
hw.optional.arm.FEAT_FP16: 1
hw.optional.arm.FEAT_SSBS: 1
hw.optional.arm.FEAT_BTI: 1
hw.optional.arm.FEAT_SME: 0
hw.optional.arm.FEAT_SME2: 0
hw.optional.arm.SME_F32F32: 0
hw.optional.arm.SME_BI32I32: 0
hw.optional.arm.SME_B16F32: 0
hw.optional.arm.SME_F16F32: 0
hw.optional.arm.SME_I8I32: 0
hw.optional.arm.SME_I16I32: 0
hw.optional.arm.FEAT_SME_F64F64: 0
hw.optional.arm.FEAT_SME_I16I64: 0
hw.optional.arm.FP_SyncExceptions: 1
hw.optional.floatingpoint: 1
hw.optional.neon: 1
hw.optional.neon_hpfp: 1
hw.optional.neon_fp16: 1
hw.optional.armv8_1_atomics: 1
hw.optional.armv8_2_fhm: 1
hw.optional.armv8_2_sha512: 1
hw.optional.armv8_2_sha3: 1
hw.optional.armv8_3_compnum: 1
hw.optional.watchpoint: 4
hw.optional.breakpoint: 6
hw.optional.armv8_crc32: 1
hw.optional.armv8_gpi: 1
hw.optional.AdvSIMD: 1
hw.optional.AdvSIMD_HPFPCvt: 1
hw.optional.ucnormal_mem: 1
hw.optional.arm64: 1
