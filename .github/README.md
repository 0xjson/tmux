<div align="center">

# 🖥️ tmux — Terminal Multiplexer

<p>
  <img src="https://img.shields.io/badge/platform-Linux%20|%20macOS%20|%20*BSD%20|%20Solaris-blue?style=flat-square&logo=linux" alt="Platform">
  <img src="https://img.shields.io/badge/license-ISC-green?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/⌨️%20layout-Colemak--DH-orange?style=flat-square" alt="Keyboard Layout">
</p>

<p>
  <b>🚀 A personal fork with Colemak-DH keybindings</b><br>
  <sub>Upstream: <a href="https://github.com/tmux/tmux">github.com/tmux/tmux</a></sub>
</p>

</div>

---

## ✨ What is tmux?

**tmux** is a terminal multiplexer that lets you create, access, and control multiple terminals from a single screen. Detach sessions and keep them running in the background, then reattach later — perfect for remote work, long-running processes, and organized development workflows.

<p align="center">
  <img src="https://img.shields.io/badge/🎯-Session%20Management-blue?style=for-the-badge" alt="Sessions">
  <img src="https://img.shields.io/badge/🪟-Window%20Management-purple?style=for-the-badge" alt="Windows">
  <img src="https://img.shields.io/badge/📦-Pane%20Splitting-green?style=for-the-badge" alt="Panes">
</p>

---

## 🎹 Colemak-DH Keybindings

This fork uses optimized **Colemak-DH** navigation keys for a more ergonomic experience:

| Key | Direction | Description |
|:---:|:---------:|:------------|
| <kbd>L</kbd> | ⬅️ Left | Navigate to left pane / previous window |
| <kbd>H</kbd> | ➡️ Right | Navigate to right pane / next window |
| <kbd>J</kbd> | ⬆️ Up | Navigate to pane above / window above |
| <kbd>K</kbd> | ⬇️ Down | Navigate to pane below / window below |

> 💡 These bindings are designed for the Colemak-DH keyboard layout, keeping navigation keys on the home row for comfortable access.

---

## 📦 Dependencies

To build tmux, you'll need:

| Package | Source |
|:--------|:-------|
| **libevent 2.x** | [GitHub Releases](https://github.com/libevent/libevent/releases/latest) |
| **ncurses** | [invisible-mirror.net](https://invisible-mirror.net/archives/ncurses/) |
| **Build tools** | C compiler (`gcc` or `clang`), `make`, `pkg-config`, `yacc`/`bison` |

**Optional:** `utempter` library for utmp(5) updates (enable with `--enable-utempter`)

---

## 🔧 Installation

### 📥 From Release Tarball

```bash
$ ./configure && make
$ sudo make install
```

### 🛠️ From Source (Latest)

Requires `autoconf`, `automake`, and `pkg-config`:

```bash
$ git clone https://github.com/tmux/tmux.git
$ cd tmux
$ sh autogen.sh
$ ./configure && make
$ sudo make install
```

---

## 📚 Documentation

| Resource | Link |
|:---------|:-----|
| 📖 Man Page | `nroff -mdoc tmux.1 \| less` |
| 📝 Example Config | `example_tmux.conf` |
| 🌐 Wiki | [github.com/tmux/tmux/wiki](https://github.com/tmux/tmux/wiki) |
| ❓ FAQ | [github.com/tmux/tmux/wiki/FAQ](https://github.com/tmux/tmux/wiki/FAQ) |
| 🎨 Bash Completion | [scop/bash-completion](https://github.com/scop/bash-completion/blob/main/completions/tmux) |

> 🐛 **Debugging:** Run tmux with `-v` and `-vv` flags to generate server and client log files in the current directory.

---

## 🤝 Contributing

Contributions are welcome! 🎉

- 🐛 **Bug reports** — Report issues you encounter
- 💡 **Feature suggestions** — Share your ideas
- 🔧 **Code contributions** — Submit pull requests

📧 **Email:** [tmux-users@googlegroups.com](mailto:jhanmar.thng@gmail.com)

🐙 **GitHub:** [Open an issue](https://github.com/tmux/tmux/issues) or [Pull Request](https://github.com/tmux/tmux/pulls)

---

## 💬 Support & Community

Join the discussion and get help:

<p align="center">
  <a href="https://groups.google.com/forum/#!forum/tmux-users">
    <img src="https://img.shields.io/badge/📧-Mailing%20List-red?style=for-the-badge" alt="Mailing List">
  </a>
</p>

**Subscribe:** Send an email to [tmux-users+subscribe@googlegroups.com](mailto:jhanmar.thng@gmail.com)

---

## 📄 License

- This `README` and `CHANGES` files → **[ISC License](https://opensource.org/licenses/ISC)**
- All other files → See license and copyright notice at the start of each file

---

<div align="center">

<p><b>Made with ❤️ for terminal enthusiasts</b></p>

<sub>🖥️ ⚡ 🚀</sub>

</div>
