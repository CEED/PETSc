-include ../../../../petscdir.mk
ALL: lib

CPPFLAGS =
CFLAGS   =
FFLAGS   =
SOURCEC  = plexland.c
SOURCECU =
SOURCEF  =
SOURCEH  = land_tensors.h
DIRS     = tutorials cuda kokkos
LIBBASE  = libpetscts
MANSEC   = TS
SUBMANSEC= LANDAU
LOCDIR   = src/ts/utils/dmplexlandau

include ${PETSC_DIR}/lib/petsc/conf/variables
include ${PETSC_DIR}/lib/petsc/conf/rules
include ${PETSC_DIR}/lib/petsc/conf/test
