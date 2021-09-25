# cool shaders
cool fragment shaders i made in glsl

---
### Uniforms

| Uniform | Contents |
| --- | --- |
| u_resolution | 2D vector containing resolution of window in pixels|
| u_time | Float containing time in milliseconds  |

---
### 2D Clouds Shader

[source code](shaders/clouds.glsl)

This is clouds shader. It uses two kinds of noise to make these cool clouds. [^noise]


![cool clouds shader](readme/1.gif)

[^noise]: https://thebookofshaders.com/11/