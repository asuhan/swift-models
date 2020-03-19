add_executable(GPT2-WikiText2
  main.swift)
target_link_libraries(GPT2-WikiText2 PRIVATE
  Datasets
  TextModels
  x10_device
  x10_tensor)


install(TARGETS GPT2-WikiText2
  DESTINATION bin)
