# cool shaders(very cool)

*cool* fragment shaders i made in glsl

---

### Uniforms

| Uniform | Contents |
| --- | --- |
| `u_resolution` | 2D vector containing resolution of window in pixels|
| `u_time` | Float containing time in milliseconds  |

---

### 2D Clouds Shader

[source code](shaders/clouds.glsl)

This is clouds shader. It uses two kinds of noise to make these cool clouds. [^noise] <br>
You may want to play around with `noiseSpeed` and `fmbSpeed` to get different results.

![cool clouds shader](readme/1.gif)

<p style="font-size: smaller">(the gif quality is bad, it  looks better)</p>

[^noise]: https://thebookofshaders.com/11/