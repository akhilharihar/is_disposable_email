# is-disposable-email
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

Python package to check if the email address belongs to one of [disposable email](http://en.wikipedia.org/wiki/Disposable_email_address) service provider like `mailinator.com`.

You can use it to detect or block accounts created with these addresses during signup process.

# Installation
Install and update using pip:

```
pip install git+https://github.com/akhilharihar/is_disposable_email.git
```

# Examples
```
import is_disposable_email

# check if the domain of the email address is disposable

result = is_disposable_email.check('dfaf@getnada.com')

# to get the list of disposable email domains

is_disposable_email.domain_list
```
# Contributing
Disposable domains in this package are grabbed from [ivolo/disposable-email-domains](https://github.com/ivolo/disposable-email-domains). To add new disposable domains, visit the contributing guide for [ivolo/disposable-email-domains](https://github.com/ivolo/disposable-email-domains)

# License

```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|
```

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.