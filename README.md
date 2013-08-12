# TOAST - Unit Testing for CodeIgniter 3.0

_Douglas Stridsberg <douglas@stridsberg.eu>_

_Jens Roland <mail@jensroland.com> [original author]_

The suite has been updated to work with CodeIgniter 3.0 and has received an overhaul regarding documentation and OO style.

## Function reference
### Assertions
* `$this->_assert_true( statement )`
* `$this->_assert_false( statement )`
* `$this->_assert_equals( statement, value )`
* `$this->_assert_not_equals( statement, value )`
* `$this->_assert_empty( statement )`
* `$this->_assert_not_empty( statement )`
* `$this->_assert_true_strict( statement )`
* `$this->_assert_false_strict( statement )`
* `$this->_assert_equals_strict( statement, value )`
* `$this->_assert_not_equals_strict( statement, value )`

### Pre/Post
* `_pre()` Identical to other frameworks' `up()`.
* `_post()` Identical to other frameworks' `down()`.

### Fail
* `$this->_fail()` Run this instead of `$this->_assert_true(false)`.

### Debug
* `$this->message` Set this to a message you want to display for a particular test.

Please see <http://jensroland.com/projects/toast/> for a full function reference.