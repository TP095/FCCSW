################################################################################
# Package: DetFCCehTrackerTkLayout
################################################################################
gaudi_subdir(DetFCCehTrackerTkLayout v1r0)

gaudi_depends_on_subdirs(GaudiKernel Detector/DetCommon)



install(DIRECTORY ${CMAKE_CURRENT_LIST_DIR}/compact DESTINATION Detector/DetFCCheTrackerTkLayout)
