add_swift_library(swiftAVFoundation IS_SDK_OVERLAY
  AVFoundation.swift
  TARGET_SDKS OSX IOS IOS_SIMULATOR TVOS TVOS_SIMULATOR
  SWIFT_MODULE_DEPENDS Foundation CoreMedia
  FRAMEWORK_DEPENDS AVFoundation)
