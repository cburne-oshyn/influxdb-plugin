static List<Map<String, String>> recommendedConfigurations() {
    def recentLTS = "2.289.1"
    def configurations = [
        [ platform: "linux", jdk: "8", jenkins: null ],
        [ platform: "windows", jdk: "8", jenkins: null ],
        [ platform: "linux", jdk: "8", jenkins: recentLTS, javaLevel: "8" ],
        [ platform: "windows", jdk: "8", jenkins: recentLTS, javaLevel: "8" ],
        [ platform: "linux", jdk: "11", jenkins: recentLTS, javaLevel: "8" ],
        [ platform: "windows", jdk: "11", jenkins: recentLTS, javaLevel: "8" ]
    ]
    return configurations
}
buildPlugin(configurations: recommendedConfigurations())
