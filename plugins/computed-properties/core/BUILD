load("//:index.bzl", "javascript_pipeline")

javascript_pipeline(
    name = "@player-ui/computed-properties-plugin",
    dependencies = [
        "@npm//tapable-ts",
    ],
    peer_dependencies = [
        "//core/player:@player-ui/player",
    ],
    test_data = [
        "//core/make-flow:@player-ui/make-flow",
    ]
)
