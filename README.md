# Demo Sphinx parsed-literals Bug

A demo project for sphinx-doc/sphinx's issue [#12287](https://github.com/sphinx-doc/sphinx/issues/12287#issuecomment-3094368182).

Modified from [localizethedocs/cmake-docs-l10n](https://github.com/localizethedocs/cmake-docs-l10n.git) at [98b2958
](https://github.com/localizethedocs/cmake-docs-l10n/commit/98b29586c437171714c36156ff7a10cb727fa5be) commit.

Run the following commands:

```bash
cmake --preset zh_TW
cmake --build out/build/zh_TW
firefox out/html/zh-tw/master/manual/cmake.1.html
```
