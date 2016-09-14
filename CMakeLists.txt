cmake_minimum_required(VERSION 2.8)
project(PTAM)
add_executable(PTAM ARDriver.cc ATANCamera.cc Bundle.cc CalibCornerPatch.cc CalibImage.cc CameraCalibrator.cc EyeGame.cc GLWindow2.cc
GLWindowMenu.cc HomographyInit.cc KeyFrame.cc Map.cc MapMaker.cc MapPoint.cc MapViewer.cc MiniPatch.cc PatchFinder.cc Relocaliser.cc
 ShiTomasi.cc SmallBlurryImage.cc System.cc Tracker.cc main.cc)