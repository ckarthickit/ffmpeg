# ffmpeg
修改后编译OK
ffmpeg
ffmpeg-0.8
ubutu 10.10 上成功编译2012‎年‎2‎月‎16‎日

记录：
#cd ffmpeg-0.8/
# ls
build_android.sh        cmdutils.h   config.log     COPYING.GPLv3     doc       ffpresets   INSTALL      libavformat  LICENSE      README      tools
build_android.sh.bak    common.mak   config.mak     COPYING.LGPLv2.1  Doxyfile  ffprobe.c   libavcodec   libavutil    MAINTAINERS  RELEASE     VERSION
cmdutils.c              config.fate  configure      COPYING.LGPLv3    ffmpeg.c  ffserver.c  libavdevice  libpostproc  Makefile     subdir.mak  version.h
cmdutils_common_opts.h  config.h     COPYING.GPLv2  CREDITS           ffplay.c  ffserver.h  libavfilter  libswscale   mt-work      tests       version.sh
# ./build_android.sh


最后生成 android 文件夹：

# ls
android                 cmdutils.d   config.h       COPYING.GPLv3     Doxyfile  ffmpeg.o   ffprobe.d   INSTALL      libavutil    Makefile    tests
build_android.sh        cmdutils.h   config.log     COPYING.LGPLv2.1  ffmpeg    ffplay.c   ffprobe_g   libavcodec   libpostproc  mt-work     tools
build_android.sh.bak    cmdutils.o   config.mak     COPYING.LGPLv3    ffmpeg.c  ffpresets  ffprobe.o   libavdevice  libswscale   README      VERSION
cmdutils.c              common.mak   configure      CREDITS           ffmpeg.d  ffprobe    ffserver.c  libavfilter  LICENSE      RELEASE     version.h
cmdutils_common_opts.h  config.fate  COPYING.GPLv2  doc               ffmpeg_g  ffprobe.c  ffserver.h  libavformat  MAINTAINERS  subdir.mak  version.sh
#


# ls ./android/
armv7-a
# ls ./android/armv7-a/
bin  include  lib  libffmpeg.so  share

