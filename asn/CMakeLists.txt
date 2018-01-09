# H2020 ESROCOS Project
# Company: GMV Aerospace & Defence S.A.U.
# Licence: GPLv2



esrocos_asn1_types_package(esrocos_types_drivers 
        CanMessage.asn
        CanOpen.asn
        JoystickCommand.asn
        pohicdriver-can.asn
        pohicdriver-ip.asn
        TimestampEstimatorStatus.asn
        IMPORT types/base)

esrocos_asn1_types_build_test(esrocos_types_drivers)
esrocos_asn1_types_install(esrocos_types_drivers ${CMAKE_INSTALL_PREFIX}/types/drivers)


