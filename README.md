# Purpose
Simple android app that gathers human heart beat from smartwatch,
displays it on watch screen, and sends that data to phone every second.

Phone job is to analyze that data and evaluate human emotional state.
It's also possible to send json with emotion data through socket for
provided IP:
```
 { "emotionType": "BORED", "heartBeat": 58, "certainty": 70}"
```

# Screenshots
![Watch](../readme_images/watch_1.png?raw=true)
![Watch2](../readme_images/watch_2.png?raw=true)
