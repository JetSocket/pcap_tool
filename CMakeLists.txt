cmake_minimum_required(VERSION 3.1...3.27)

project(
  pcap_tool
  VERSION 1.0
  LANGUAGES C)

add_executable(pcap_tool pcap_tool.c)

target_link_libraries(pcap_tool PRIVATE pcap)