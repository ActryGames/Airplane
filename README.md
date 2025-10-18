<!-- Variables -->
# Airplane
~~A stable, optimized, well supported 1.17 Paper fork.~~ old fork of paper, no longer supported

[Homepage][home] - [Downloads][downloads] - [Blog][blog] - [Discord][discord] - [airplane.yml][wiki]

## Features

- **30% faster hoppers** over both Tuinity & Paper
- **Improved entity performance** from a reduction in ticking entity behavior based on how far away they are from the player.
- **Reduced GC times & frequency** from removing useless allocations, which also improves CPU performance.
- **Fast raytracing** which improves performance of any entity which utilizes line of sight, mainly Villagers.
- **Built-in profiler** which has 0 performance hit and easy to read metrics for both server owners and developers.
- Faster crafting, reduction in uselessly loaded chunks, faster entity ticking, faster block ticking, faster bat spawning, and more!
- Plugin compatibility with Paper & Tuinity plugins.
- [Read more about our features.][about]

## Downloads
The latest JAR file can be downloaded from [the downloads page][downloads].

## Building

```bash
./gradlew build
```

Or building a Paperclip JAR for distribution:

```bash
./gradlew paperclip
```

## License
Patches are licensed under GPL-3.0.  
All other files are licensed under MIT.
