Local Manifest to Build CM11 For Xperia E (nanhu)

Please use nanhu_bt.xml if you wan't to compile with working bluetooth as the original nanhu.xml doesn't include bluetooth-modified repo's. 

=========================================

If you get an error while compiling related to OMXCodec.cpp about 'nBitsPerSample', delete the line mentioned in the error. It will probably be something along the line of:

param.nBitsPerSample = bitsPerSample;

==========================================
