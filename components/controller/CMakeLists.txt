idf_component_register(
  SRCS
  "controller.cpp"
  INCLUDE_DIRS
  "include"
  REQUIRES
  esp_timer
  power
  PRIV_REQUIRES
  app
  app_update
  mqtt_app
  nvs_data
  task
  utils)
