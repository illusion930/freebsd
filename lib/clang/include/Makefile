# $FreeBSD$

.include <bsd.own.mk>

LLVM_SRCS= ${.CURDIR}/../../../contrib/llvm

.include "../clang.build.mk"

.PATH: ${LLVM_SRCS}/tools/clang/lib/Headers

INCSDIR=${INCLUDEDIR}/clang/3.5.1

INCS=	__wmmintrin_aes.h \
	__wmmintrin_pclmul.h \
	altivec.h \
	ammintrin.h \
	arm_acle.h \
	avx2intrin.h \
	avxintrin.h \
	bmi2intrin.h \
	bmiintrin.h \
	cpuid.h \
	emmintrin.h \
	f16cintrin.h \
	fma4intrin.h \
	fmaintrin.h \
	ia32intrin.h \
	immintrin.h \
	lzcntintrin.h \
	mm3dnow.h \
	mm_malloc.h \
	mmintrin.h \
	module.modulemap \
	nmmintrin.h \
	pmmintrin.h \
	popcntintrin.h \
	prfchwintrin.h \
	rdseedintrin.h \
	rtmintrin.h \
	shaintrin.h \
	smmintrin.h \
	tbmintrin.h \
	tmmintrin.h \
	wmmintrin.h \
	x86intrin.h \
	xmmintrin.h \
	xopintrin.h \
	${GENINCS}
GENINCS= arm_neon.h
CLEANFILES= ${GENINCS}

.include <bsd.prog.mk>
