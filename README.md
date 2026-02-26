# Renderer

A renderer using SFML that is easy to use for my stupid brain.

The drawing loop should be:

```cpp
Renderer::init(width, height);
while(Renderer::loop())
{
    // draw your stuff here
}
```
