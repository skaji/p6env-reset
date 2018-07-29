# p6env reset

p6env for https://github.com/skaji/plenv-reset

## Synopsis

1. First prepare tarballs for fresh Perl installations.
    ```
    p6env install 2018.06
    cd $(p6env root)/versions
    tar cJf 2018.06.tar.xz 2018.06
    ```
2. Hack with Perl6 2018.06....
3. When you want a fresh Perl6 2018.06
    ```
    p6env reset 2018.06
    ```

## Install

```
git clone https://github.com/skaji/p6env-reset $(p6env root)/plugins/p6env-reset
```

## Author

Shoichi Kaji

## License

The same terms as the Perl 5
