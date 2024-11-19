#
# Copyright 2024 NXP
#
# SPDX-License-Identifier: MIT
#


if(CONFIG_MCUX_COMPONENT_middleware.aws_iot.jobs)
    mcux_add_source(
        SOURCES source/jobs.c
                source/include/jobs.h
    )
    mcux_add_include(
        INCLUDES source/include
    )
endif()
