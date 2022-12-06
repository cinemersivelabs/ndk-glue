> ⚠️ **This project is no longer being actively maintained**
>
> _It's recommended that new projects look at using the [android-activity](https://crates.io/crates/android-activity)
> crate for building standalone Rust applications on Android_


This standalone repository was split, for posterity, from the [android-ndk-rs](https://github.com/rust-windowing/android-ndk-rs) repository like this:

```
git clone https://github.com/newren/git-filter-repo
git clone https://github.com/rust-windowing/android-ndk-rs.git ndk-glue
cd ndk-glue
py ../git-filter-repo/git-filter-repo --path ndk-glue --path ndk-macro --path ndk-examples --path-rename ndk-examples:examples --path LICENSE-APACHE --path LICENSE-MIT --path Cargo.toml --path rustfmt.toml --path .github --path .gitignore
```

The last `android-ndk-rs` commit that's part of this repository is https://github.com/rust-windowing/android-ndk-rs/commit/107f03e3858bdced3a7a898e43b339b73d7fc1af