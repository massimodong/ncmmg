A naive cmm code generator (with an automatically testing fool.)

### Usage
To compile the code generator, type

    make

To start testing, type

    ./run.sh

(you need to comment out outputs in irsim:main.cc, because this run.sh uses a naive diff.)
(All test data that you're wrong will be copied into tests/)