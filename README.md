# mruby-gpu-image

> **Image processing for mruby on the GPU: a small part of scipy.ndimage, plus colormaps and PNG output.**

🚧 **Planned** as part of the Ruby Association Grant 2026 project "Expanding GPU computing libraries for mruby" ([selection result](https://www.ruby.or.jp/en/news/20261102)). Nothing is usable here yet.

## What it will provide

- `gaussian_filter`, `zoom`, and small convolutions
- Colormaps (values to colours) and PNG output, so results can be checked as images

The shaders are written for this gem instead of pulling in a large library such as OpenCV. Like the other gems, it will link only against the Vulkan loader. It builds on [mruby-gpu-runtime](https://github.com/yujiteshima/mruby-gpu-runtime) and [mruby-gpu-narray](https://github.com/yujiteshima/mruby-gpu-narray).

Progress is tracked in the [GitHub Project](https://github.com/users/yujiteshima/projects/3).

## License

MIT
