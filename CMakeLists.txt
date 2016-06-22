set(GFFREAD_SOURCE_FILES
        ../gclib/GArgs.cpp
        ../gclib/GBase.cpp
        ../gclib/GStr.cpp
        ../gclib/gdna.cpp
        ../gclib/gff.cpp
        ../gclib/codons.cpp
        ../gclib/GFastaIndex.cpp
        ../gclib/GFaSeqGet.cpp
        gff_utils.cpp
        )
add_executable(gffread gffread.cpp ${GFFREAD_SOURCE_FILES})
set_target_properties(gffread PROPERTIES RUNTIME_OUTPUT_DIRECTORY ${Isoaux_BINDIR})