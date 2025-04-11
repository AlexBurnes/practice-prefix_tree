# Student Practice C++: Prefix tree

**Search value in a prefix tree by number**

Imlements prefix search tree algorigthm, search values belonging to numeric range or numeric prefix.

## Author

Aleksey.Ozhigov <AlexBurnes@gmail.com>

## Version

0.1.0

## Change log

For detail history changes, see [CHANGELOG](CHANGELOG.md)

## Build

    git submodule init
    git submodule update
    docker build --tag practice_prefix_tree:latest --network host --progress=plain .

## Test Coverage

To view test coverage, run a Docker container:

    docker run -d --rm --name practice_prefix_tree --publish 8081:80 practice_prefix_tree

Then open your browser at [Coverage](http://localhost:8081)

## Code Style Check

For checking code style formatting the clang-format-19 utility is used.
The format is defined in style_format.txt, which is based on
[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

    clang-format-19 --style="file:style_format.txt" source

# License

This work is distributed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0), see
[LICENSE](https://github.com:AlexBurnes/practice-prefix_tree/blob/master/LICENSE) for more information.
