# Python

## Naming
> If object is internal, which means can only used in modules (filename)
> or private or protected in class, use '_' as prefix.

* lower_with_under
  * Module (filename)
  * Packages (directories)
  * Functions
  * rest of all

* CapWords
  * Classes
  * Exception

* CAPS_WITH_UNDER
  * Global/Class Constants


### Function Naming
Function is action, should always start with a verb.


* 檢查動詞
  * check(檢查): Return bool, used of yes/no, good/bad situation
  * assert(檢查+output error)
  * ensure(檢查+彌補動作)
  * test(檢查): interact with system and return result
* 刪除動詞
  * clear(清空容器)
  * delete(刪除): Delete something in container which things inside is dependent to others. Ex. words in sentense
  * Remove(刪除): Delete something in container which can be seperate easily. Ex. product in buying list
  * cancel(取消)
  * dismiss(忽略)

## Linter

Please use flake8 package.

```shell
vim ~/.config/flake8

# in vim editor
[flake8]
max-line-length = 96
```

---

**Reference**

[Google Codin Style Reference](https://tw-google-styleguide.readthedocs.io/en/latest/google-python-styleguide/contents.html)

[The use of verb](https://github.com/EngTW/English-for-Programmers)
