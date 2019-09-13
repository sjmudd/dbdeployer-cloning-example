## dbdeployer-cloning-example

### What is it?

This is a simple script to show how to clone a [MySQL](https://www.mysql.com) 8.0.17+ server using [MySQL native cloning](https://dev.mysql.com/doc/refman/8.0/en/clone-plugin.html).
This uses [dbdeployer](https://github.com/datacharmer/dbdeployer).
See:
* the script [clone_script](https://github.com/sjmudd/dbdeployer-cloning-example/blob/master/clone_script) for details of how to set this up
* [sample_output.log](https://github.com/sjmudd/dbdeployer-cloning-example/blob/master/sample_output.log) for an example of what you would see.

### Requirements

* [dbdeployer](https://github.com/datacharmer/dbdeployer).
* MySQL 8.0.17 installed where dbdeployer can find it. It can also grab it for you.
* the [sample dataset](https://github.com/datacharmer/test_db) installed to ~/data/employees.

### Contact

Simon Mudd <sjmudd@pobox.com>
