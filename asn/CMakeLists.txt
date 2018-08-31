# H2020 ESROCOS Project
# Company: GMV Aerospace & Defence S.A.U.
# Licence: GPLv2

esrocos_asn1_types_package(esrocos_types_fused 
        Map.asn
        IMPORT types/base types/sensor_samples)

#esrocos_asn1_types_build_test(esrocos_types_fused)
esrocos_asn1_types_install(esrocos_types_fused ${CMAKE_INSTALL_PREFIX}/types/fused)

