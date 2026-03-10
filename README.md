[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (-------------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (-------------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be useful,)
[comment]: <> (but WITHOUT ANY WARRANTY; without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the)
[comment]: <> (GNU Affero General Public License for more details.)

[comment]: <> (You should have received a copy of the GNU Affero General Public)
[comment]: <> (License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Git Bundle Colab

Creates a git bundle file for a git repository
on a Google Colab instance.

To maximize speed, it uses a ramdisk.

For comparison, the example repository
used, linux kernel, checks out in
over 20 minutes on disk, while on
a ram disk it takes around 15 minutes in total.

The repository is then moved on disk while
again the bundle created from local checkout
is written in RAM and then
moved on disk.

You can run the program at this repo
from Gogole Colab through the following
url

https://colab.research.google.com/github/themartiancompany/git-bundle-colab/blob/master/git-bundle-colab/git-bundle-colab.ipynb

# Source availability

This program has been officially published
on the the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`git-bundle-colab`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To retrieve the sources for this program
on your computer just type

```bash
ur \
  git-bundle-colab
```

A censorable HTTP Github mirror of the recipe published there,
is hosted on
[git-bundle-colab-ur](
  https://github.com/themartiancompany/git-bundle-colab-ur).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
