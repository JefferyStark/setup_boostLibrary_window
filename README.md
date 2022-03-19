# setup_boostLibrary_window


Visual Studio 2019 -  bootstrap vc142
Visual Studio 2017 -  bootstrap vc141
Visual Studio 2015 -  bootstrap vc140
BOOST_ROOT=C:\DevSoft\boost_1_73_0\boost

./b2



-----------------------------------------------

isual Studio 2019 - 32bit Build 
 b2 --build-dir=build/x86 address-model=32 threading=multi --build-type=complete --stagedir=./stage/x86 --toolset=msvc-14.2 -j 12  
 
 Visual Studio 2019 - 64bit Build
 b2 --build-dir=build/x64 address-model=64 threading=multi --build-type=complete --stagedir=./stage/x64 --toolset=msvc-14.2 -j 12  
 
 Visual Studio 2017 - 32bit Build 
 b2 --build-dir=build/x86 address-model=32 threading=multi --build-type=complete --stagedir=./stage/x86 --toolset=msvc-14.1 -j 12  
 
 Visual Studio 2017 - 64bit Build
 b2 --build-dir=build/x64 address-model=64 threading=multi --build-type=complete --stagedir=./stage/x64 --toolset=msvc-14.1 -j 12  
 
 Visual Studio 2015 - 32bit Build 
 b2 --build-dir=build/x86 address-model=32 threading=multi --build-type=complete --stagedir=./stage/x86 --toolset=msvc-14.0 -j 12  
 
 Visual Studio 2015 - 64bit Build
 b2 --build-dir=build/x64 address-model=64 threading=multi --build-type=complete --stagedir=./stage/x64 --toolset=msvc-14.0 -j 12  
 
 
 ------------------------------------------
 
 
 https://www.boost.org/doc/libs/1_74_0/more/getting_started/windows.html
