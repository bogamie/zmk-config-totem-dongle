# Copyright (c) 2024 The ZMK Contributors
# SPDX-License-Identifier: MIT

target_sources_ifdef(CONFIG_TOTEM_BATTERY_HID_REPORT app PRIVATE battery_hid.c)
