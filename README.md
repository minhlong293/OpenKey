# OpenKey (fork)

This repository is a fork of the original [OpenKey](https://github.com/tuyenvm/OpenKey) project, maintained to fix bugs found in the original.

## Bugs fixed in this fork

- Stuck capitals on Windows: tone-marked vowels come out uppercase (`cá` becomes `cÁ`) and the language-switch hotkey stops working until OpenKey is restarted, caused by a stale tracked Shift state in the Windows keyboard hook. See upstream issue [tuyenvm/OpenKey#320](https://github.com/tuyenvm/OpenKey/issues/320).

## License

This fork remains under the original project's GPL license; see [LICENSE](LICENSE).
