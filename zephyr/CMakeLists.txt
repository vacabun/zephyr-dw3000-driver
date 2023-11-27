# SPDX-License-Identifier: Apache-2.0
zephyr_include_directories(.)
add_subdirectory_ifdef(CONFIG_DW3000 dwt_uwb_driver)
add_subdirectory_ifdef(CONFIG_DW3000 platform)
add_subdirectory_ifdef(CONFIG_DW3000 shared_data)
add_subdirectory_ifdef(CONFIG_DW3000 MAC_802_15_4)
