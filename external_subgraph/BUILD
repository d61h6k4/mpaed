load("@mediapipe//mediapipe/framework/tool:mediapipe_graph.bzl", "mediapipe_simple_subgraph")


mediapipe_simple_subgraph(
    name = "autoflip_face_detection_subgraph",
    graph = "face_detection_subgraph.pbtxt",
    register_as = "AutoFlipFaceDetectionSubgraph",
    visibility = ["//visibility:public"],
    deps = [
        "//mediapipe/graphs/face_detection:desktop_tflite_calculators",
    ],
)
