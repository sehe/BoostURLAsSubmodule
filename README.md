# BoostURLAsSubmodule

Steps to build:

    git clone --recurse-submodules https://github.com/sehe/BoostURLAsSubmodule
    cd BoostURLAsSubmodule/
    BOOST_ROOT=~/custom/boost_1_79_0/ cmake -B build .
    make -C build/

If you need, override BOOST_ROOT:

    BOOST_ROOT=~/custom/boost_1_79_0/ cmake -B build .
