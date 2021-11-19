
            ______ ______                                  
           / ____// ____/____ ___   ____   ___   ____ _
          / /_   / /_   / __ `__ \ / __ \ / _ \ / __ `/
         / __/  / __/  / / / / / // /_/ //  __// /_/ /
        /_/    /_/    /_/ /_/ /_// .___/ \___/ \__, /
                                /_/           /____/


                build: ffmpeg-git-20211117-amd64-static.tar.xz
              version: a35101aae36583450be4881a5cde2a904a489d84

                  gcc: 8.3.0
                 yasm: 1.3.0.36.ge2569
                 nasm: 2.15.05

               libaom: 3.2.0-231-gd2345ca3b
               libass: 0.15.2
               libgme: 0.6.3
               libsrt: 1.4.4
               libvpx: 1.11.0-30-g888bafc78
              libvmaf: 1.5.3
              libx264: 0.164.3075 
              libx265: 3.5+1-f0c1022b6
              libxvid: 1.3.7 
              libwebp: 0.6.1 
              libzimg: 3.0.3
              libzvbi: 0.2.36
             libdav1d: 0.9.2
            libgnutls: 3.7.2
            libtheora: 1.2.0alpha1+git
            libfrei0r: 1.6.1-2
           libvidstab: 1.20
          libfreetype: 2.9.1-3+deb10u1
          libharfbuzz: 3.1.1
          libopenjpeg: 2.4.0 

              libalsa: 1.2.4
              libsoxr: 0.1.3
              libopus: 1.3.1
             libspeex: 1.2
            libvorbis: 1.3.7
           libmp3lame: 3.100 
        librubberband: 1.8.2
       libvo-amrwbenc: 0.1.3-1+b1
    libopencore-amrnb: 0.1.3-2.1+b2
    libopencore-amrwb: 0.1.3-2.1+b2


     Notes:  A limitation of statically linking glibc is the loss of DNS resolution. Installing
             nscd through your package manager will fix this.

             The vmaf filter needs external files to work- see model/000-README.TXT


      This static build is licensed under the GNU General Public License version 3.

      
      Patreon:  https://www.patreon.com/johnvansickle
      Paypal:   https://www.paypal.me/johnvansickle 
      Ethereum: 0x491f0b4bAd15FF178257D9Fa81ce87baa8b6E242 
      Bitcoin:  3ErDdF5JeG9RMx2DXwXEeunrsc5dVHjmeq 
      Dogecoin: DH4WZPTjwKh2TarQhkpQrKjHZ9kNTkiMNL

      email: john.vansickle@gmail.com
      irc:   relaxed @ irc://chat.freenode.net #ffmpeg
      url:   https://johnvansickle.com/ffmpeg/


Codecs:
 D..... = Decoding supported
 .E.... = Encoding supported
 ..V... = Video codec
 ..A... = Audio codec
 ..S... = Subtitle codec
 ...I.. = Intra frame-only codec
 ....L. = Lossy compression
 .....S = Lossless compression
 -------
 D.VI.S 012v                 Uncompressed 4:2:2 10-bit
 D.V.L. 4xm                  4X Movie
 D.VI.S 8bps                 QuickTime 8BPS video
 .EVIL. a64_multi            Multicolor charset for Commodore 64 (encoders: a64multi )
 .EVIL. a64_multi5           Multicolor charset for Commodore 64, extended with 5th color (colram) (encoders: a64multi5 )
 D.V..S aasc                 Autodesk RLE
 D.V.L. agm                  Amuse Graphics Movie
 D.VIL. aic                  Apple Intermediate Codec
 DEVI.S alias_pix            Alias/Wavefront PIX image
 DEVIL. amv                  AMV Video
 D.V.L. anm                  Deluxe Paint Animation
 D.V.L. ansi                 ASCII/ANSI art
 DEV..S apng                 APNG (Animated Portable Network Graphics) image
 D.V.L. arbc                 Gryphon's Anim Compressor
 D.V.L. argo                 Argonaut Games Video
 DEVIL. asv1                 ASUS V1
 DEVIL. asv2                 ASUS V2
 D.VIL. aura                 Auravision AURA
 D.VIL. aura2                Auravision Aura 2
 DEV.L. av1                  Alliance for Open Media AV1 (decoders: libdav1d libaom-av1 av1 ) (encoders: libaom-av1 )
 D.V... avrn                 Avid AVI Codec
 DEVI.S avrp                 Avid 1:1 10-bit RGB Packer
 D.V.L. avs                  AVS (Audio Video Standard) video
 ..V.L. avs2                 AVS2-P2/IEEE1857.4
 ..V.L. avs3                 AVS3-P2/IEEE1857.10
 DEVI.S avui                 Avid Meridien Uncompressed
 DEVI.S ayuv                 Uncompressed packed MS 4:4:4:4
 D.V.L. bethsoftvid          Bethesda VID video
 D.V.L. bfi                  Brute Force & Ignorance
 D.V.L. binkvideo            Bink video
 D.VI.. bintext              Binary text
 D.VI.S bitpacked            Bitpacked
 DEVI.S bmp                  BMP (Windows and OS/2 bitmap)
 D.V..S bmv_video            Discworld II BMV video
 D.VI.S brender_pix          BRender PIX image
 D.V.L. c93                  Interplay C93
 D.V.L. cavs                 Chinese AVS (Audio Video Standard) (AVS1-P2, JiZhun profile)
 D.V.L. cdgraphics           CD Graphics video
 D.V..S cdtoons              CDToons video
 D.VIL. cdxl                 Commodore CDXL video
 DEV.L. cfhd                 GoPro CineForm HD
 DEV.L. cinepak              Cinepak
 D.V.L. clearvideo           Iterated Systems ClearVideo
 DEVIL. cljr                 Cirrus Logic AccuPak
 D.VI.S cllc                 Canopus Lossless Codec
 D.V.L. cmv                  Electronic Arts CMV video (decoders: eacmv )
 D.V... cpia                 CPiA video format
 D.VILS cri                  Cintel RAW
 D.V..S cscd                 CamStudio (decoders: camstudio )
 D.VIL. cyuv                 Creative YUV (CYUV)
 ..V.LS daala                Daala
 D.VILS dds                  DirectDraw Surface image decoder
 D.V.L. dfa                  Chronomaster DFA
 DEV.LS dirac                Dirac (encoders: vc2 )
 DEVIL. dnxhd                VC3/DNxHD
 DEVI.S dpx                  DPX (Digital Picture Exchange) image
 D.V.L. dsicinvideo          Delphine Software International CIN video
 DEVIL. dvvideo              DV (Digital Video)
 D.V..S dxa                  Feeble Files/ScummVM DXA
 D.VI.S dxtory               Dxtory
 D.VIL. dxv                  Resolume DXV
 D.V.L. escape124            Escape 124
 D.V.L. escape130            Escape 130
 DEVILS exr                  OpenEXR image
 DEV..S ffv1                 FFmpeg video codec #1
 DEVI.S ffvhuff              Huffyuv FFmpeg variant
 D.V.L. fic                  Mirillis FIC
 DEVI.S fits                 FITS (Flexible Image Transport System)
 DEV..S flashsv              Flash Screen Video v1
 DEV.L. flashsv2             Flash Screen Video v2
 D.V..S flic                 Autodesk Animator Flic video
 DEV.L. flv1                 FLV / Sorenson Spark / Sorenson H.263 (Flash Video) (decoders: flv ) (encoders: flv )
 D.V..S fmvc                 FM Screen Capture Codec
 D.VI.S fraps                Fraps
 D.VI.S frwu                 Forward Uncompressed
 D.V.L. g2m                  Go2Meeting
 D.V.L. gdv                  Gremlin Digital Video
 D.V.L. gem                  GEM Raster image
 DEV..S gif                  CompuServe GIF (Graphics Interchange Format)
 DEV.L. h261                 H.261
 DEV.L. h263                 H.263 / H.263-1996, H.263+ / H.263-1998 / H.263 version 2 (decoders: h263 h263_v4l2m2m ) (encoders: h263 h263_v4l2m2m )
 D.V.L. h263i                Intel H.263
 DEV.L. h263p                H.263+ / H.263-1998 / H.263 version 2
 DEV.LS h264                 H.264 / AVC / MPEG-4 AVC / MPEG-4 part 10 (decoders: h264 h264_v4l2m2m ) (encoders: libx264 libx264rgb h264_v4l2m2m )
 D.VIL. hap                  Vidvox Hap
 DEV.L. hevc                 H.265 / HEVC (High Efficiency Video Coding) (decoders: hevc hevc_v4l2m2m ) (encoders: libx265 hevc_v4l2m2m )
 D.V.L. hnm4video            HNM 4 video
 D.VIL. hq_hqa               Canopus HQ/HQA
 D.VIL. hqx                  Canopus HQX
 DEVI.S huffyuv              HuffYUV
 D.VI.S hymt                 HuffYUV MT
 D.V.L. idcin                id Quake II CIN video (decoders: idcinvideo )
 D.VI.. idf                  iCEDraw text
 D.V.L. iff_ilbm             IFF ACBM/ANIM/DEEP/ILBM/PBM/RGB8/RGBN (decoders: iff )
 D.V.L. imm4                 Infinity IMM4
 D.V.L. imm5                 Infinity IMM5
 D.V.L. indeo2               Intel Indeo 2
 D.V.L. indeo3               Intel Indeo 3
 D.V.L. indeo4               Intel Indeo Video Interactive 4
 D.V.L. indeo5               Intel Indeo Video Interactive 5
 D.V.L. interplayvideo       Interplay MVE video
 D.VIL. ipu                  IPU Video
 DEVILS jpeg2000             JPEG 2000 (decoders: jpeg2000 libopenjpeg ) (encoders: jpeg2000 libopenjpeg )
 DEVILS jpegls               JPEG-LS
 D.VIL. jv                   Bitmap Brothers JV video
 D.V.L. kgv1                 Kega Game Video
 D.V.L. kmvc                 Karl Morton's video codec
 D.VI.S lagarith             Lagarith lossless
 .EVI.S ljpeg                Lossless JPEG
 D.VI.S loco                 LOCO
 D.V.L. lscr                 LEAD Screen Capture
 D.VI.S m101                 Matrox Uncompressed SD
 D.V.L. mad                  Electronic Arts Madcow Video (decoders: eamad )
 DEVI.S magicyuv             MagicYUV video
 D.VIL. mdec                 Sony PlayStation MDEC (Motion DECoder)
 D.V.L. mimic                Mimic
 DEVIL. mjpeg                Motion JPEG
 D.VIL. mjpegb               Apple MJPEG-B
 D.V.L. mmvideo              American Laser Games MM Video
 D.V.L. mobiclip             MobiClip Video
 D.V.L. motionpixels         Motion Pixels video
 DEV.L. mpeg1video           MPEG-1 video (decoders: mpeg1video mpeg1_v4l2m2m )
 DEV.L. mpeg2video           MPEG-2 video (decoders: mpeg2video mpegvideo mpeg2_v4l2m2m )
 DEV.L. mpeg4                MPEG-4 part 2 (decoders: mpeg4 mpeg4_v4l2m2m ) (encoders: mpeg4 libxvid mpeg4_v4l2m2m )
 D.V.L. msa1                 MS ATC Screen
 D.VI.S mscc                 Mandsoft Screen Capture Codec
 D.V.L. msmpeg4v1            MPEG-4 part 2 Microsoft variant version 1
 DEV.L. msmpeg4v2            MPEG-4 part 2 Microsoft variant version 2
 DEV.L. msmpeg4v3            MPEG-4 part 2 Microsoft variant version 3 (decoders: msmpeg4 ) (encoders: msmpeg4 )
 D.VI.S msp2                 Microsoft Paint (MSP) version 2
 D.V..S msrle                Microsoft RLE
 D.V.L. mss1                 MS Screen 1
 D.VIL. mss2                 MS Windows Media Video V9 Screen
 DEV.L. msvideo1             Microsoft Video 1
 D.VI.S mszh                 LCL (LossLess Codec Library) MSZH
 D.V.L. mts2                 MS Expression Encoder Screen
 D.V.L. mv30                 MidiVid 3.0
 D.VIL. mvc1                 Silicon Graphics Motion Video Compressor 1
 D.VIL. mvc2                 Silicon Graphics Motion Video Compressor 2
 D.V.L. mvdv                 MidiVid VQ
 D.VIL. mvha                 MidiVid Archive Codec
 D.V..S mwsc                 MatchWare Screen Capture Codec
 D.V.L. mxpeg                Mobotix MxPEG video
 D.VIL. notchlc              NotchLC
 D.V.L. nuv                  NuppelVideo/RTJPEG
 D.V.L. paf_video            Amazing Studio Packed Animation File Video
 DEVI.S pam                  PAM (Portable AnyMap) image
 DEVI.S pbm                  PBM (Portable BitMap) image
 DEVI.S pcx                  PC Paintbrush PCX image
 DEVI.S pfm                  PFM (Portable FloatMap) image
 DEVI.S pgm                  PGM (Portable GrayMap) image
 DEVI.S pgmyuv               PGMYUV (Portable GrayMap YUV) image
 D.VI.S pgx                  PGX (JPEG2000 Test Format)
 D.V.L. photocd              Kodak Photo CD
 D.VIL. pictor               Pictor/PC Paint
 D.VIL. pixlet               Apple Pixlet
 DEV..S png                  PNG (Portable Network Graphics) image
 DEVI.S ppm                  PPM (Portable PixelMap) image
 DEVIL. prores               Apple ProRes (iCodec Pro) (encoders: prores prores_aw prores_ks )
 D.VIL. prosumer             Brooktree ProSumer Video
 D.VI.S psd                  Photoshop PSD file
 D.VIL. ptx                  V.Flash PTX image
 D.VI.S qdraw                Apple QuickDraw
 D.V.L. qpeg                 Q-team QPEG
 DEV..S qtrle                QuickTime Animation (RLE) video
 DEVI.S r10k                 AJA Kona 10-bit RGB Codec
 DEVI.S r210                 Uncompressed RGB 10-bit
 D.V.L. rasc                 RemotelyAnywhere Screen Capture
 DEVI.S rawvideo             raw video
 D.VIL. rl2                  RL2 video
 DEV.L. roq                  id RoQ video (decoders: roqvideo ) (encoders: roqvideo )
 DEV.L. rpza                 QuickTime video (RPZA)
 D.V..S rscc                 innoHeim/Rsupport Screen Capture Codec
 DEV.L. rv10                 RealVideo 1.0
 DEV.L. rv20                 RealVideo 2.0
 D.V.L. rv30                 RealVideo 3.0
 D.V.L. rv40                 RealVideo 4.0
 D.V.L. sanm                 LucasArts SANM/SMUSH video
 D.V.LS scpr                 ScreenPressor
 D.V..S screenpresso         Screenpresso
 D.V.L. sga                  Digital Pictures SGA Video
 DEVI.S sgi                  SGI image
 D.VI.S sgirle               SGI RLE 8-bit
 D.VI.S sheervideo           BitJazz SheerVideo
 D.V.L. simbiosis_imx        Simbiosis Interactive IMX Video
 D.V.L. smackvideo           Smacker video (decoders: smackvid )
 DEV.L. smc                  QuickTime Graphics (SMC)
 D.VIL. smvjpeg              Sigmatel Motion Video
 DEV.LS snow                 Snow
 D.VIL. sp5x                 Sunplus JPEG (SP5X)
 DEVIL. speedhq              NewTek SpeedHQ
 D.VI.S srgc                 Screen Recorder Gold Codec
 DEVI.S sunrast              Sun Rasterfile image
 ..V..S svg                  Scalable Vector Graphics
 DEV.L. svq1                 Sorenson Vector Quantizer 1 / Sorenson Video 1 / SVQ1
 D.V.L. svq3                 Sorenson Vector Quantizer 3 / Sorenson Video 3 / SVQ3
 DEVI.S targa                Truevision Targa image
 D.VI.S targa_y216           Pinnacle TARGA CineWave YUV16
 D.V.L. tdsc                 TDSC
 D.V.L. tgq                  Electronic Arts TGQ video (decoders: eatgq )
 D.V.L. tgv                  Electronic Arts TGV video (decoders: eatgv )
 DEV.L. theora               Theora (encoders: libtheora )
 D.VIL. thp                  Nintendo Gamecube THP video
 D.V.L. tiertexseqvideo      Tiertex Limited SEQ video
 DEVI.S tiff                 TIFF image
 D.VIL. tmv                  8088flex TMV
 D.V.L. tqi                  Electronic Arts TQI video (decoders: eatqi )
 D.V.L. truemotion1          Duck TrueMotion 1.0
 D.V.L. truemotion2          Duck TrueMotion 2.0
 D.VIL. truemotion2rt        Duck TrueMotion 2.0 Real Time
 D.V..S tscc                 TechSmith Screen Capture Codec (decoders: camtasia )
 D.V.L. tscc2                TechSmith Screen Codec 2
 D.VIL. txd                  Renderware TXD (TeXture Dictionary) image
 D.V.L. ulti                 IBM UltiMotion (decoders: ultimotion )
 DEVI.S utvideo              Ut Video
 DEVI.S v210                 Uncompressed 4:2:2 10-bit
 D.VI.S v210x                Uncompressed 4:2:2 10-bit
 DEVI.S v308                 Uncompressed packed 4:4:4
 DEVI.S v408                 Uncompressed packed QT 4:4:4:4
 DEVI.S v410                 Uncompressed 4:4:4 10-bit
 D.V.L. vb                   Beam Software VB
 D.VI.S vble                 VBLE Lossless Codec
 D.V.L. vc1                  SMPTE VC-1 (decoders: vc1 vc1_v4l2m2m )
 D.V.L. vc1image             Windows Media Video 9 Image v2
 D.VIL. vcr1                 ATI VCR1
 D.VIL. vixl                 Miro VideoXL (decoders: xl )
 D.V.L. vmdvideo             Sierra VMD video
 D.V..S vmnc                 VMware Screen Codec / VMware Video
 D.V.L. vp3                  On2 VP3
 D.V.L. vp4                  On2 VP4
 D.V.L. vp5                  On2 VP5
 D.V.L. vp6                  On2 VP6
 D.V.L. vp6a                 On2 VP6 (Flash version, with alpha channel)
 D.V.L. vp6f                 On2 VP6 (Flash version)
 D.V.L. vp7                  On2 VP7
 DEV.L. vp8                  On2 VP8 (decoders: vp8 vp8_v4l2m2m libvpx ) (encoders: libvpx vp8_v4l2m2m )
 DEV.L. vp9                  Google VP9 (decoders: vp9 vp9_v4l2m2m libvpx-vp9 ) (encoders: libvpx-vp9 )
 ..V.L. vvc                  H.266 / VVC (Versatile Video Coding)
 D.V..S wcmv                 WinCAM Motion Video
 DEVILS webp                 WebP (encoders: libwebp_anim libwebp )
 DEV.L. wmv1                 Windows Media Video 7
 DEV.L. wmv2                 Windows Media Video 8
 D.V.L. wmv3                 Windows Media Video 9
 D.V.L. wmv3image            Windows Media Video 9 Image
 D.VIL. wnv1                 Winnov WNV1
 DEV..S wrapped_avframe      AVFrame to AVPacket passthrough
 D.V.L. ws_vqa               Westwood Studios VQA (Vector Quantized Animation) video (decoders: vqavideo )
 D.V.L. xan_wc3              Wing Commander III / Xan
 D.V.L. xan_wc4              Wing Commander IV / Xxan
 D.VI.. xbin                 eXtended BINary text
 DEVI.S xbm                  XBM (X BitMap) image
 DEVIL. xface                X-face image
 D.VI.S xpm                  XPM (X PixMap) image
 DEVI.S xwd                  XWD (X Window Dump) image
 DEVI.S y41p                 Uncompressed YUV 4:1:1 12-bit
 D.VI.S ylc                  YUY2 Lossless Codec
 D.V.L. yop                  Psygnosis YOP Video
 DEVI.S yuv4                 Uncompressed packed 4:2:0
 D.V..S zerocodec            ZeroCodec Lossless Video
 DEVI.S zlib                 LCL (LossLess Codec Library) ZLIB
 DEV..S zmbv                 Zip Motion Blocks Video
 ..AIL. 4gv                  4GV (Fourth Generation Vocoder)
 D.AIL. 8svx_exp             8SVX exponential
 D.AIL. 8svx_fib             8SVX fibonacci
 DEAIL. aac                  AAC (Advanced Audio Coding) (decoders: aac aac_fixed )
 D.AIL. aac_latm             AAC LATM (Advanced Audio Coding LATM syntax)
 DEAIL. ac3                  ATSC A/52A (AC-3) (decoders: ac3 ac3_fixed ) (encoders: ac3 ac3_fixed )
 D.AIL. acelp.kelvin         Sipro ACELP.KELVIN
 D.AIL. adpcm_4xm            ADPCM 4X Movie
 DEAIL. adpcm_adx            SEGA CRI ADX ADPCM
 D.AIL. adpcm_afc            ADPCM Nintendo Gamecube AFC
 D.AIL. adpcm_agm            ADPCM AmuseGraphics Movie AGM
 D.AIL. adpcm_aica           ADPCM Yamaha AICA
 DEAIL. adpcm_argo           ADPCM Argonaut Games
 D.AIL. adpcm_ct             ADPCM Creative Technology
 D.AIL. adpcm_dtk            ADPCM Nintendo Gamecube DTK
 D.AIL. adpcm_ea             ADPCM Electronic Arts
 D.AIL. adpcm_ea_maxis_xa    ADPCM Electronic Arts Maxis CDROM XA
 D.AIL. adpcm_ea_r1          ADPCM Electronic Arts R1
 D.AIL. adpcm_ea_r2          ADPCM Electronic Arts R2
 D.AIL. adpcm_ea_r3          ADPCM Electronic Arts R3
 D.AIL. adpcm_ea_xas         ADPCM Electronic Arts XAS
 DEAIL. adpcm_g722           G.722 ADPCM (decoders: g722 ) (encoders: g722 )
 DEAIL. adpcm_g726           G.726 ADPCM (decoders: g726 ) (encoders: g726 )
 DEAIL. adpcm_g726le         G.726 ADPCM little-endian (decoders: g726le ) (encoders: g726le )
 D.AIL. adpcm_ima_acorn      ADPCM IMA Acorn Replay
 DEAIL. adpcm_ima_alp        ADPCM IMA High Voltage Software ALP
 DEAIL. adpcm_ima_amv        ADPCM IMA AMV
 D.AIL. adpcm_ima_apc        ADPCM IMA CRYO APC
 DEAIL. adpcm_ima_apm        ADPCM IMA Ubisoft APM
 D.AIL. adpcm_ima_cunning    ADPCM IMA Cunning Developments
 D.AIL. adpcm_ima_dat4       ADPCM IMA Eurocom DAT4
 D.AIL. adpcm_ima_dk3        ADPCM IMA Duck DK3
 D.AIL. adpcm_ima_dk4        ADPCM IMA Duck DK4
 D.AIL. adpcm_ima_ea_eacs    ADPCM IMA Electronic Arts EACS
 D.AIL. adpcm_ima_ea_sead    ADPCM IMA Electronic Arts SEAD
 D.AIL. adpcm_ima_iss        ADPCM IMA Funcom ISS
 D.AIL. adpcm_ima_moflex     ADPCM IMA MobiClip MOFLEX
 D.AIL. adpcm_ima_mtf        ADPCM IMA Capcom's MT Framework
 D.AIL. adpcm_ima_oki        ADPCM IMA Dialogic OKI
 DEAIL. adpcm_ima_qt         ADPCM IMA QuickTime
 D.AIL. adpcm_ima_rad        ADPCM IMA Radical
 D.AIL. adpcm_ima_smjpeg     ADPCM IMA Loki SDL MJPEG
 DEAIL. adpcm_ima_ssi        ADPCM IMA Simon & Schuster Interactive
 DEAIL. adpcm_ima_wav        ADPCM IMA WAV
 DEAIL. adpcm_ima_ws         ADPCM IMA Westwood
 DEAIL. adpcm_ms             ADPCM Microsoft
 D.AIL. adpcm_mtaf           ADPCM MTAF
 D.AIL. adpcm_psx            ADPCM Playstation
 D.AIL. adpcm_sbpro_2        ADPCM Sound Blaster Pro 2-bit
 D.AIL. adpcm_sbpro_3        ADPCM Sound Blaster Pro 2.6-bit
 D.AIL. adpcm_sbpro_4        ADPCM Sound Blaster Pro 4-bit
 DEAIL. adpcm_swf            ADPCM Shockwave Flash
 D.AIL. adpcm_thp            ADPCM Nintendo THP
 D.AIL. adpcm_thp_le         ADPCM Nintendo THP (Little-Endian)
 D.AIL. adpcm_vima           LucasArts VIMA audio
 D.AIL. adpcm_xa             ADPCM CDROM XA
 DEAIL. adpcm_yamaha         ADPCM Yamaha
 D.AIL. adpcm_zork           ADPCM Zork
 DEAI.S alac                 ALAC (Apple Lossless Audio Codec)
 DEAIL. amr_nb               AMR-NB (Adaptive Multi-Rate NarrowBand) (decoders: amrnb libopencore_amrnb ) (encoders: libopencore_amrnb )
 DEAIL. amr_wb               AMR-WB (Adaptive Multi-Rate WideBand) (decoders: amrwb libopencore_amrwb ) (encoders: libvo_amrwbenc )
 D.AI.S ape                  Monkey's Audio
 DEAIL. aptx                 aptX (Audio Processing Technology for Bluetooth)
 DEAIL. aptx_hd              aptX HD (Audio Processing Technology for Bluetooth)
 D.AIL. atrac1               ATRAC1 (Adaptive TRansform Acoustic Coding)
 D.AIL. atrac3               ATRAC3 (Adaptive TRansform Acoustic Coding 3)
 D.AI.S atrac3al             ATRAC3 AL (Adaptive TRansform Acoustic Coding 3 Advanced Lossless)
 D.AIL. atrac3p              ATRAC3+ (Adaptive TRansform Acoustic Coding 3+) (decoders: atrac3plus )
 D.AI.S atrac3pal            ATRAC3+ AL (Adaptive TRansform Acoustic Coding 3+ Advanced Lossless) (decoders: atrac3plusal )
 D.AIL. atrac9               ATRAC9 (Adaptive TRansform Acoustic Coding 9)
 D.AIL. avc                  On2 Audio for Video Codec (decoders: on2avc )
 D.AIL. binkaudio_dct        Bink Audio (DCT)
 D.AIL. binkaudio_rdft       Bink Audio (RDFT)
 D.AIL. bmv_audio            Discworld II BMV audio
 ..AIL. celt                 Constrained Energy Lapped Transform (CELT)
 ..AIL. codec2               codec2 (very low bitrate speech codec)
 DEAIL. comfortnoise         RFC 3389 Comfort Noise
 D.AIL. cook                 Cook / Cooker / Gecko (RealAudio G2)
 D.AIL. derf_dpcm            DPCM Xilam DERF
 D.AIL. dolby_e              Dolby E
 D.AIL. dsd_lsbf             DSD (Direct Stream Digital), least significant bit first
 D.AIL. dsd_lsbf_planar      DSD (Direct Stream Digital), least significant bit first, planar
 D.AIL. dsd_msbf             DSD (Direct Stream Digital), most significant bit first
 D.AIL. dsd_msbf_planar      DSD (Direct Stream Digital), most significant bit first, planar
 D.AIL. dsicinaudio          Delphine Software International CIN audio
 D.AIL. dss_sp               Digital Speech Standard - Standard Play mode (DSS SP)
 D.AI.S dst                  DST (Direct Stream Transfer)
 DEAILS dts                  DCA (DTS Coherent Acoustics) (decoders: dca ) (encoders: dca )
 D.AIL. dvaudio              DV audio
 DEAIL. eac3                 ATSC A/52B (AC-3, E-AC-3)
 D.AIL. evrc                 EVRC (Enhanced Variable Rate Codec)
 D.AIL. fastaudio            MobiClip FastAudio
 DEAI.S flac                 FLAC (Free Lossless Audio Codec)
 DEAIL. g723_1               G.723.1
 D.AIL. g729                 G.729
 D.AIL. gremlin_dpcm         DPCM Gremlin
 D.AIL. gsm                  GSM
 D.AIL. gsm_ms               GSM Microsoft variant
 D.AIL. hca                  CRI HCA
 D.AIL. hcom                 HCOM Audio
 D.AIL. iac                  IAC (Indeo Audio Coder)
 D.AIL. ilbc                 iLBC (Internet Low Bitrate Codec)
 D.AIL. imc                  IMC (Intel Music Coder)
 D.AIL. interplay_dpcm       DPCM Interplay
 D.AIL. interplayacm         Interplay ACM
 D.AIL. mace3                MACE (Macintosh Audio Compression/Expansion) 3:1
 D.AIL. mace6                MACE (Macintosh Audio Compression/Expansion) 6:1
 D.AIL. metasound            Voxware MetaSound
 DEA..S mlp                  MLP (Meridian Lossless Packing)
 D.AIL. mp1                  MP1 (MPEG audio layer 1) (decoders: mp1 mp1float )
 DEAIL. mp2                  MP2 (MPEG audio layer 2) (decoders: mp2 mp2float ) (encoders: mp2 mp2fixed )
 DEAIL. mp3                  MP3 (MPEG audio layer 3) (decoders: mp3float mp3 ) (encoders: libmp3lame )
 D.AIL. mp3adu               ADU (Application Data Unit) MP3 (MPEG audio layer 3) (decoders: mp3adufloat mp3adu )
 D.AIL. mp3on4               MP3onMP4 (decoders: mp3on4float mp3on4 )
 D.AI.S mp4als               MPEG-4 Audio Lossless Coding (ALS) (decoders: als )
 ..A.L. mpegh_3d_audio       MPEG-H 3D Audio
 D.AIL. msnsiren             MSN Siren
 D.AIL. musepack7            Musepack SV7 (decoders: mpc7 )
 D.AIL. musepack8            Musepack SV8 (decoders: mpc8 )
 DEAIL. nellymoser           Nellymoser Asao
 DEAIL. opus                 Opus (Opus Interactive Audio Codec) (decoders: opus libopus ) (encoders: opus libopus )
 D.AIL. paf_audio            Amazing Studio Packed Animation File Audio
 DEAIL. pcm_alaw             PCM A-law / G.711 A-law
 D.AI.S pcm_bluray           PCM signed 16|20|24-bit big-endian for Blu-ray media
 DEAI.S pcm_dvd              PCM signed 20|24-bit big-endian
 D.AI.S pcm_f16le            PCM 16.8 floating point little-endian
 D.AI.S pcm_f24le            PCM 24.0 floating point little-endian
 DEAI.S pcm_f32be            PCM 32-bit floating point big-endian
 DEAI.S pcm_f32le            PCM 32-bit floating point little-endian
 DEAI.S pcm_f64be            PCM 64-bit floating point big-endian
 DEAI.S pcm_f64le            PCM 64-bit floating point little-endian
 D.AI.S pcm_lxf              PCM signed 20-bit little-endian planar
 DEAIL. pcm_mulaw            PCM mu-law / G.711 mu-law
 DEAI.S pcm_s16be            PCM signed 16-bit big-endian
 DEAI.S pcm_s16be_planar     PCM signed 16-bit big-endian planar
 DEAI.S pcm_s16le            PCM signed 16-bit little-endian
 DEAI.S pcm_s16le_planar     PCM signed 16-bit little-endian planar
 DEAI.S pcm_s24be            PCM signed 24-bit big-endian
 DEAI.S pcm_s24daud          PCM D-Cinema audio signed 24-bit
 DEAI.S pcm_s24le            PCM signed 24-bit little-endian
 DEAI.S pcm_s24le_planar     PCM signed 24-bit little-endian planar
 DEAI.S pcm_s32be            PCM signed 32-bit big-endian
 DEAI.S pcm_s32le            PCM signed 32-bit little-endian
 DEAI.S pcm_s32le_planar     PCM signed 32-bit little-endian planar
 DEAI.S pcm_s64be            PCM signed 64-bit big-endian
 DEAI.S pcm_s64le            PCM signed 64-bit little-endian
 DEAI.S pcm_s8               PCM signed 8-bit
 DEAI.S pcm_s8_planar        PCM signed 8-bit planar
 D.AI.S pcm_sga              PCM SGA
 DEAI.S pcm_u16be            PCM unsigned 16-bit big-endian
 DEAI.S pcm_u16le            PCM unsigned 16-bit little-endian
 DEAI.S pcm_u24be            PCM unsigned 24-bit big-endian
 DEAI.S pcm_u24le            PCM unsigned 24-bit little-endian
 DEAI.S pcm_u32be            PCM unsigned 32-bit big-endian
 DEAI.S pcm_u32le            PCM unsigned 32-bit little-endian
 DEAI.S pcm_u8               PCM unsigned 8-bit
 DEAIL. pcm_vidc             PCM Archimedes VIDC
 D.AIL. qcelp                QCELP / PureVoice
 D.AIL. qdm2                 QDesign Music Codec 2
 D.AIL. qdmc                 QDesign Music
 DEAIL. ra_144               RealAudio 1.0 (14.4K) (decoders: real_144 ) (encoders: real_144 )
 D.AIL. ra_288               RealAudio 2.0 (28.8K) (decoders: real_288 )
 D.AI.S ralf                 RealAudio Lossless
 DEAIL. roq_dpcm             DPCM id RoQ
 DEAI.S s302m                SMPTE 302M
 DEAIL. sbc                  SBC (low-complexity subband codec)
 D.AIL. sdx2_dpcm            DPCM Squareroot-Delta-Exact
 D.AI.S shorten              Shorten
 D.AIL. sipr                 RealAudio SIPR / ACELP.NET
 D.AIL. siren                Siren
 D.AIL. smackaudio           Smacker audio (decoders: smackaud )
 ..AIL. smv                  SMV (Selectable Mode Vocoder)
 D.AIL. sol_dpcm             DPCM Sol
 DEAI.. sonic                Sonic
 .EAI.. sonicls              Sonic lossless
 DEAIL. speex                Speex (decoders: speex libspeex ) (encoders: libspeex )
 D.A..S tak                  TAK (Tom's lossless Audio Kompressor)
 DEA..S truehd               TrueHD
 D.AIL. truespeech           DSP Group TrueSpeech
 DEAI.S tta                  TTA (True Audio)
 D.AIL. twinvq               VQF TwinVQ
 D.AIL. vmdaudio             Sierra VMD audio
 DEAIL. vorbis               Vorbis (decoders: vorbis libvorbis ) (encoders: vorbis libvorbis )
 D.AI.. wavesynth            Wave synthesis pseudo-codec
 DEAILS wavpack              WavPack
 D.AIL. westwood_snd1        Westwood Audio (SND1) (decoders: ws_snd1 )
 D.AI.S wmalossless          Windows Media Audio Lossless
 D.AIL. wmapro               Windows Media Audio 9 Professional
 DEAIL. wmav1                Windows Media Audio 1
 DEAIL. wmav2                Windows Media Audio 2
 D.AIL. wmavoice             Windows Media Audio Voice
 D.AIL. xan_dpcm             DPCM Xan
 D.AIL. xma1                 Xbox Media Audio 1
 D.AIL. xma2                 Xbox Media Audio 2
 ..D... bin_data             binary data
 ..D... dvd_nav_packet       DVD Nav packet
 ..D... epg                  Electronic Program Guide
 ..D... klv                  SMPTE 336M Key-Length-Value (KLV) metadata
 ..D... mpegts               raw MPEG-TS stream
 ..D... otf                  OpenType font
 ..D... scte_35              SCTE 35 Message Queue
 ..D... timed_id3            timed ID3 metadata
 ..D... ttf                  TrueType font
 ..S... arib_caption         ARIB STD-B24 caption
 DES... ass                  ASS (Advanced SSA) subtitle (decoders: ssa ass ) (encoders: ssa ass )
 DES... dvb_subtitle         DVB subtitles (decoders: dvbsub ) (encoders: dvbsub )
 D.S... dvb_teletext         DVB teletext (decoders: libzvbi_teletextdec )
 DES... dvd_subtitle         DVD subtitles (decoders: dvdsub ) (encoders: dvdsub )
 D.S... eia_608              EIA-608 closed captions (decoders: cc_dec )
 D.S... hdmv_pgs_subtitle    HDMV Presentation Graphic Stream subtitles (decoders: pgssub )
 ..S... hdmv_text_subtitle   HDMV Text subtitle
 D.S... jacosub              JACOsub subtitle
 D.S... microdvd             MicroDVD subtitle
 DES... mov_text             MOV text
 D.S... mpl2                 MPL2 subtitle
 D.S... pjs                  PJS (Phoenix Japanimation Society) subtitle
 D.S... realtext             RealText subtitle
 D.S... sami                 SAMI subtitle
 ..S... srt                  SubRip subtitle with embedded timing
 ..S... ssa                  SSA (SubStation Alpha) subtitle
 D.S... stl                  Spruce subtitle format
 DES... subrip               SubRip subtitle (decoders: srt subrip ) (encoders: srt subrip )
 D.S... subviewer            SubViewer subtitle
 D.S... subviewer1           SubViewer v1 subtitle
 DES... text                 raw UTF-8 text
 .ES... ttml                 Timed Text Markup Language
 D.S... vplayer              VPlayer subtitle
 DES... webvtt               WebVTT subtitle
 DES... xsub                 XSUB


Filters:
  T.. = Timeline support
  .S. = Slice threading
  ..C = Command support
  A = Audio input/output
  V = Video input/output
  N = Dynamic number and/or type of input/output
  | = Source or sink filter
 ... abench            A->A       Benchmark part of a filtergraph.
 ..C acompressor       A->A       Audio compressor.
 ... acontrast         A->A       Simple audio dynamic range compression/expansion filter.
 ... acopy             A->A       Copy the input audio unchanged to the output.
 ... acue              A->A       Delay filtering to match a cue.
 ... acrossfade        AA->A      Cross fade two input audio streams.
 .S. acrossover        A->N       Split audio into per-bands streams.
 ..C acrusher          A->A       Reduce audio bit resolution.
 TS. adeclick          A->A       Remove impulsive noise from input audio.
 TS. adeclip           A->A       Remove clipping from input audio.
 TS. adecorrelate      A->A       Apply decorrelation to input audio.
 T.. adelay            A->A       Delay one or more audio channels.
 TSC adenorm           A->A       Remedy denormals by adding extremely low-level noise.
 ... aderivative       A->A       Compute derivative of input audio.
 ... aecho             A->A       Add echoing to the audio.
 TSC aemphasis         A->A       Audio emphasis.
 T.. aeval             A->A       Filter audio signal according to a specified expression.
 T.C aexciter          A->A       Enhance high frequency part of audio.
 T.C afade             A->A       Fade in/out input audio.
 TSC afftdn            A->A       Denoise audio samples using FFT.
 T.. afftfilt          A->A       Apply arbitrary expressions to samples in frequency domain.
 .SC afir              N->N       Apply Finite Impulse Response filter with supplied coefficients in additional stream(s).
 ... aformat           A->A       Convert the input audio to one of the specified formats.
 TSC afreqshift        A->A       Apply frequency shifting to input audio.
 TSC afwtdn            A->A       Denoise audio stream using Wavelets.
 T.C agate             A->A       Audio gate.
 .S. aiir              A->N       Apply Infinite Impulse Response filter with supplied coefficients.
 ... aintegral         A->A       Compute integral of input audio.
 ... ainterleave       N->A       Temporally interleave audio inputs.
 T.. alatency          A->A       Report audio filtering latency.
 T.C alimiter          A->A       Audio lookahead limiter.
 TSC allpass           A->A       Apply a two-pole all-pass filter.
 ... aloop             A->A       Loop audio samples.
 ... amerge            N->A       Merge two or more audio streams into a single multi-channel stream.
 T.. ametadata         A->A       Manipulate audio frame metadata.
 ..C amix              N->A       Audio mixing.
 ... amultiply         AA->A      Multiply two audio streams.
 TSC anequalizer       A->N       Apply high-order audio parametric multi band equalizer.
 TSC anlmdn            A->A       Reduce broadband noise from stream using Non-Local Means.
 .SC anlms             AA->A      Apply Normalized Least-Mean-Squares algorithm to first audio stream.
 ... anull             A->A       Pass the source unchanged to the output.
 T.. apad              A->A       Pad audio with silence.
 T.. aperms            A->A       Set permissions for the output audio frame.
 ... aphaser           A->A       Add a phasing effect to the audio.
 TSC aphaseshift       A->A       Apply phase shifting to input audio.
 TSC apsyclip          A->A       Audio Psychoacoustic Clipper.
 ... apulsator         A->A       Audio pulsator.
 ... arealtime         A->A       Slow down filtering to match realtime.
 ... aresample         A->A       Resample audio data.
 ... areverse          A->A       Reverse an audio clip.
 TSC arnndn            A->A       Reduce noise from speech using Recurrent Neural Networks.
 ... asdr              AA->A      Measure Audio Signal-to-Distortion Ratio.
 ... asegment          A->N       Segment audio stream.
 ... aselect           A->N       Select audio frames to pass in output.
 ... asendcmd          A->A       Send commands to filters.
 ... asetnsamples      A->A       Set the number of samples for each output audio frames.
 ... asetpts           A->A       Set PTS for the output audio frame.
 ... asetrate          A->A       Change the sample rate without altering the data.
 ... asettb            A->A       Set timebase for the audio output link.
 ... ashowinfo         A->A       Show textual information for each audio frame.
 T.. asidedata         A->A       Manipulate audio frame side data.
 TSC asoftclip         A->A       Audio Soft Clipper.
 ... asplit            A->N       Pass on the audio input to N audio outputs.
 .S. astats            A->A       Show time domain statistics about audio frames.
 ..C astreamselect     N->N       Select audio streams
 TSC asubboost         A->A       Boost subwoofer frequencies.
 TSC asubcut           A->A       Cut subwoofer frequencies.
 TSC asupercut         A->A       Cut super frequencies.
 TSC asuperpass        A->A       Apply high order Butterworth band-pass filter.
 TSC asuperstop        A->A       Apply high order Butterworth band-stop filter.
 ..C atempo            A->A       Adjust audio tempo.
 TSC atilt             A->A       Apply spectral tilt to audio.
 ... atrim             A->A       Pick one continuous section from the input, drop the rest.
 ... axcorrelate       AA->A      Cross-correlate two audio streams.
 TSC bandpass          A->A       Apply a two-pole Butterworth band-pass filter.
 TSC bandreject        A->A       Apply a two-pole Butterworth band-reject filter.
 TSC bass              A->A       Boost or cut lower frequencies.
 TSC biquad            A->A       Apply a biquad IIR filter with the given coefficients.
 ... channelmap        A->A       Remap audio channels.
 ... channelsplit      A->N       Split audio into per-channel streams.
 ... chorus            A->A       Add a chorus effect to the audio.
 ... compand           A->A       Compress or expand audio dynamic range.
 ... compensationdelay A->A       Audio Compensation Delay Line.
 T.C crossfeed         A->A       Apply headphone crossfeed filter.
 TSC crystalizer       A->A       Simple audio noise sharpening filter.
 T.. dcshift           A->A       Apply a DC shift to the audio.
 T.. deesser           A->A       Apply de-essing to the audio.
 ... drmeter           A->A       Measure audio dynamic range.
 T.C dynaudnorm        A->A       Dynamic Audio Normalizer.
 ... earwax            A->A       Widen the stereo image.
 ... ebur128           A->N       EBU R128 scanner.
 TSC equalizer         A->A       Apply two-pole peaking equalization (EQ) filter.
 T.C extrastereo       A->A       Increase difference between stereo audio channels.
 ..C firequalizer      A->A       Finite Impulse Response Equalizer.
 ... flanger           A->A       Apply a flanging effect to the audio.
 ... haas              A->A       Apply Haas Stereo Enhancer.
 ... hdcd              A->A       Apply High Definition Compatible Digital (HDCD) decoding.
 .S. headphone         N->A       Apply headphone binaural spatialization with HRTFs in additional streams.
 TSC highpass          A->A       Apply a high-pass filter with 3dB point frequency.
 TSC highshelf         A->A       Apply a high shelf filter.
 ... join              N->A       Join multiple audio streams into multi-channel output.
 ... loudnorm          A->A       EBU R128 loudness normalization
 TSC lowpass           A->A       Apply a low-pass filter with 3dB point frequency.
 TSC lowshelf          A->A       Apply a low shelf filter.
 ... mcompand          A->A       Multiband Compress or expand audio dynamic range.
 ... pan               A->A       Remix channels with coefficients (panning).
 ... replaygain        A->A       ReplayGain scanner.
 ..C rubberband        A->A       Apply time-stretching and pitch-shifting.
 ..C sidechaincompress AA->A      Sidechain compressor.
 T.C sidechaingate     AA->A      Audio sidechain gate.
 ... silencedetect     A->A       Detect silence.
 ... silenceremove     A->A       Remove silence.
 T.C speechnorm        A->A       Speech Normalizer.
 T.C stereotools       A->A       Apply various stereo tools.
 T.C stereowiden       A->A       Apply stereo widening effect.
 ... superequalizer    A->A       Apply 18 band equalization filter.
 .S. surround          A->A       Apply audio surround upmix filter.
 TSC treble            A->A       Boost or cut upper frequencies.
 ... tremolo           A->A       Apply tremolo effect.
 ... vibrato           A->A       Apply vibrato effect.
 T.C volume            A->A       Change input volume.
 ... volumedetect      A->A       Detect audio volume.
 ... aevalsrc          |->A       Generate an audio signal generated by an expression.
 ... afirsrc           |->A       Generate a FIR coefficients audio stream.
 ... anoisesrc         |->A       Generate a noise audio signal.
 ... anullsrc          |->A       Null audio source, return empty audio frames.
 ... hilbert           |->A       Generate a Hilbert transform FIR coefficients.
 ... sinc              |->A       Generate a sinc kaiser-windowed low-pass, high-pass, band-pass, or band-reject FIR coefficients.
 ... sine              |->A       Generate sine wave audio signal.
 ... anullsink         A->|       Do absolutely nothing with the input audio.
 ... addroi            V->V       Add region of interest to frame.
 ... alphaextract      V->V       Extract an alpha channel as a grayscale image component.
 T.. alphamerge        VV->V      Copy the luma value of the second input into the alpha channel of the first input.
 TSC amplify           V->V       Amplify changes between successive video frames.
 ... ass               V->V       Render ASS subtitles onto input video using the libass library.
 TSC atadenoise        V->V       Apply an Adaptive Temporal Averaging Denoiser.
 T.C avgblur           V->V       Apply Average Blur filter.
 T.C bbox              V->V       Compute bounding box for each frame.
 ... bench             V->V       Benchmark part of a filtergraph.
 TSC bilateral         V->V       Apply Bilateral filter.
 T.. bitplanenoise     V->V       Measure bit plane noise.
 .S. blackdetect       V->V       Detect video intervals that are (almost) black.
 ... blackframe        V->V       Detect frames that are (almost) black.
 TSC blend             VV->V      Blend two video frames into each other.
 TS. bm3d              N->V       Block-Matching 3D denoiser.
 T.. boxblur           V->V       Blur the input.
 TS. bwdif             V->V       Deinterlace the input image.
 TSC cas               V->V       Contrast Adaptive Sharpen.
 TSC chromahold        V->V       Turns a certain color range into gray.
 TSC chromakey         V->V       Turns a certain color into transparency. Operates on YUV colors.
 TSC chromanr          V->V       Reduce chrominance noise.
 TSC chromashift       V->V       Shift chroma.
 ... ciescope          V->V       Video CIE scope.
 T.. codecview         V->V       Visualize information about some codecs.
 TSC colorbalance      V->V       Adjust the color balance.
 TSC colorchannelmixer V->V       Adjust colors by mixing color channels.
 TSC colorcontrast     V->V       Adjust color contrast between RGB components.
 TSC colorcorrect      V->V       Adjust color white balance selectively for blacks and whites.
 TSC colorize          V->V       Overlay a solid color on the video stream.
 TSC colorkey          V->V       Turns a certain color into transparency. Operates on RGB colors.
 TSC colorhold         V->V       Turns a certain color range into gray. Operates on RGB colors.
 TSC colorlevels       V->V       Adjust the color levels.
 TS. colormatrix       V->V       Convert color matrix.
 TS. colorspace        V->V       Convert between colorspaces.
 TSC colortemperature  V->V       Adjust color temperature of video.
 TSC convolution       V->V       Apply convolution filter.
 TS. convolve          VV->V      Convolve first video stream with second video stream.
 ... copy              V->V       Copy the input video unchanged to the output.
 ... cover_rect        V->V       Find and cover a user specified object.
 ..C crop              V->V       Crop the input video.
 T.. cropdetect        V->V       Auto-detect crop size.
 ... cue               V->V       Delay filtering to match a cue.
 TSC curves            V->V       Adjust components curves.
 .SC datascope         V->V       Video data analysis.
 T.C dblur             V->V       Apply Directional Blur filter.
 TS. dctdnoiz          V->V       Denoise frames using 2D DCT.
 TSC deband            V->V       Debands video.
 T.C deblock           V->V       Deblock video.
 ... decimate          N->V       Decimate frames (post field matching filter).
 TS. deconvolve        VV->V      Deconvolve first video stream with second video stream.
 TS. dedot             V->V       Reduce cross-luminance and cross-color.
 TSC deflate           V->V       Apply deflate effect.
 ... deflicker         V->V       Remove temporal frame luminance variations.
 ... dejudder          V->V       Remove judder produced by pullup.
 T.. delogo            V->V       Remove logo from input video.
 T.. derain            V->V       Apply derain filter to the input.
 ... deshake           V->V       Stabilize shaky video.
 TSC despill           V->V       Despill video.
 ... detelecine        V->V       Apply an inverse telecine pattern.
 TSC dilation          V->V       Apply dilation effect.
 T.. displace          VVV->V     Displace pixels.
 ... dnn_classify      V->V       Apply DNN classify filter to the input.
 ... dnn_detect        V->V       Apply DNN detect filter to the input.
 ... dnn_processing    V->V       Apply DNN processing filter to the input.
 .S. doubleweave       V->V       Weave input video fields into double number of frames.
 T.C drawbox           V->V       Draw a colored box on the input video.
 ... drawgraph         V->V       Draw a graph using input video metadata.
 T.C drawgrid          V->V       Draw a colored grid on the input video.
 T.C drawtext          V->V       Draw text on top of video frames using libfreetype library.
 T.. edgedetect        V->V       Detect and draw edge.
 ... elbg              V->V       Apply posterize effect, using the ELBG algorithm.
 T.. entropy           V->V       Measure video frames entropy.
 .S. epx               V->V       Scale the input using EPX algorithm.
 T.C eq                V->V       Adjust brightness, contrast, gamma, and saturation.
 TSC erosion           V->V       Apply erosion effect.
 TSC estdif            V->V       Apply Edge Slope Tracing deinterlace.
 TSC exposure          V->V       Adjust exposure of the video stream.
 ... extractplanes     V->N       Extract planes as grayscale frames.
 TS. fade              V->V       Fade in/out input video.
 TSC fftdnoiz          V->V       Denoise frames using 3D FFT.
 TS. fftfilt           V->V       Apply arbitrary expressions to pixels in frequency domain.
 ... field             V->V       Extract a field from the input video.
 ... fieldhint         V->V       Field matching using hints.
 ... fieldmatch        N->V       Field matching for inverse telecine.
 T.. fieldorder        V->V       Set the field order.
 T.C fillborders       V->V       Fill borders of the input video.
 ... find_rect         V->V       Find a user specified object.
 T.. floodfill         V->V       Fill area with same color with another color.
 ... format            V->V       Convert the input video to one of the specified pixel formats.
 ... fps               V->V       Force constant framerate.
 ... framepack         VV->V      Generate a frame packed stereoscopic video.
 .S. framerate         V->V       Upsamples or downsamples progressive source between specified frame rates.
 T.. framestep         V->V       Select one frame every N frames.
 ... freezedetect      V->V       Detects frozen video input.
 ... freezeframes      VV->V      Freeze video frames.
 T.C frei0r            V->V       Apply a frei0r effect.
 T.. fspp              V->V       Apply Fast Simple Post-processing filter.
 TSC gblur             V->V       Apply Gaussian Blur filter.
 TS. geq               V->V       Apply generic equation to each pixel.
 T.. gradfun           V->V       Debands video quickly using gradients.
 ... graphmonitor      V->V       Show various filtergraph stats.
 TS. grayworld         V->V       Adjust white balance using LAB gray world algorithm
 TS. greyedge          V->V       Estimates scene illumination by grey edge assumption.
 TSC guided            N->V       Apply Guided filter.
 TSC haldclut          VV->V      Adjust colors using a Hald CLUT.
 TS. hflip             V->V       Horizontally flip the input video.
 T.. histeq            V->V       Apply global color histogram equalization.
 ... histogram         V->V       Compute and draw a histogram.
 TSC hqdn3d            V->V       Apply a High Quality 3D Denoiser.
 .S. hqx               V->V       Scale the input by 2, 3 or 4 using the hq*x magnification algorithm.
 .S. hstack            N->V       Stack video inputs horizontally.
 TSC hsvhold           V->V       Turns a certain HSV range into gray.
 TSC hsvkey            V->V       Turns a certain HSV range into transparency. Operates on YUV colors.
 T.C hue               V->V       Adjust the hue and saturation of the input video.
 TSC huesaturation     V->V       Apply hue-saturation-intensity adjustments.
 ... hwdownload        V->V       Download a hardware frame to a normal frame
 ... hwmap             V->V       Map hardware frames
 ... hwupload          V->V       Upload a normal frame to a hardware frame
 T.. hysteresis        VV->V      Grow first stream into second stream by connecting components.
 TS. identity          VV->V      Calculate the Identity between two video streams.
 ... idet              V->V       Interlace detect Filter.
 T.C il                V->V       Deinterleave or interleave fields.
 TSC inflate           V->V       Apply inflate effect.
 ... interlace         V->V       Convert progressive video into interlaced.
 ... interleave        N->V       Temporally interleave video inputs.
 ... kerndeint         V->V       Apply kernel deinterlacing to the input.
 TSC kirsch            V->V       Apply kirsch operator.
 TSC lagfun            V->V       Slowly update darker pixels.
 T.. latency           V->V       Report video filtering latency.
 TSC lenscorrection    V->V       Rectify the image by correcting for lens distortion.
 ... libvmaf           VV->V      Calculate the VMAF between two video streams.
 TSC limitdiff         N->V       Apply filtering with limiting difference.
 TSC limiter           V->V       Limit pixels components to the specified range.
 ... loop              V->V       Loop video frames.
 TSC lumakey           V->V       Turns a certain luma into transparency.
 TSC lut               V->V       Compute and apply a lookup table to the RGB/YUV input video.
 TSC lut1d             V->V       Adjust colors using a 1D LUT.
 TSC lut2              VV->V      Compute and apply a lookup table from two video inputs.
 TSC lut3d             V->V       Adjust colors using a 3D LUT.
 TSC lutrgb            V->V       Compute and apply a lookup table to the RGB input video.
 TSC lutyuv            V->V       Compute and apply a lookup table to the YUV input video.
 TSC maskedclamp       VVV->V     Clamp first stream with second stream and third stream.
 TSC maskedmax         VVV->V     Apply filtering with maximum difference of two streams.
 TSC maskedmerge       VVV->V     Merge first stream with second stream using third stream as mask.
 TSC maskedmin         VVV->V     Apply filtering with minimum difference of two streams.
 TSC maskedthreshold   VV->V      Pick pixels comparing absolute difference of two streams with threshold.
 TSC maskfun           V->V       Create Mask.
 TSC median            V->V       Apply Median filter.
 ... mergeplanes       N->V       Merge planes.
 ... mestimate         V->V       Generate motion vectors.
 T.. metadata          V->V       Manipulate video frame metadata.
 T.. midequalizer      VV->V      Apply Midway Equalization.
 ... minterpolate      V->V       Frame rate conversion using Motion Interpolation.
 TSC mix               N->V       Mix video inputs.
 TSC monochrome        V->V       Convert video to gray using custom color filter.
 T.C morpho            VV->V      Apply Morphological filter.
 ... mpdecimate        V->V       Remove near-duplicate frames.
 TS. msad              VV->V      Calculate the MSAD between two video streams.
 TSC negate            V->V       Negate input video.
 TS. nlmeans           V->V       Non-local means denoiser.
 TSC nnedi             V->V       Apply neural network edge directed interpolation intra-only deinterlacer.
 ... noformat          V->V       Force libavfilter not to use any of the specified pixel formats for the input to the next filter.
 TS. noise             V->V       Add noise.
 T.C normalize         V->V       Normalize RGB video.
 ... null              V->V       Pass the source unchanged to the output.
 T.C oscilloscope      V->V       2D Video Oscilloscope.
 TSC overlay           VV->V      Overlay a video source on top of the input.
 T.. owdenoise         V->V       Denoise using wavelets.
 ... pad               V->V       Pad the input video.
 ... palettegen        V->V       Find the optimal palette for a given stream.
 ... paletteuse        VV->V      Use a palette to downsample an input video stream.
 T.. perms             V->V       Set permissions for the output video frame.
 TS. perspective       V->V       Correct the perspective of video.
 T.C phase             V->V       Phase shift fields.
 ... photosensitivity  V->V       Filter out photosensitive epilepsy seizure-inducing flashes.
 ... pixdesctest       V->V       Test pixel format definitions.
 T.C pixscope          V->V       Pixel data analysis.
 T.C pp                V->V       Filter video using libpostproc.
 T.. pp7               V->V       Apply Postprocessing 7 filter.
 TS. premultiply       N->V       PreMultiply first stream with first plane of second stream.
 TSC prewitt           V->V       Apply prewitt operator.
 TSC pseudocolor       V->V       Make pseudocolored video frames.
 TS. psnr              VV->V      Calculate the PSNR between two video streams.
 ... pullup            V->V       Pullup from field sequence to frames.
 T.. qp                V->V       Change video quantization parameters.
 ... random            V->V       Return random frames.
 TSC readeia608        V->V       Read EIA-608 Closed Caption codes from input video and write them to frame metadata.
 ... readvitc          V->V       Read vertical interval timecode and write it to frame metadata.
 ... realtime          V->V       Slow down filtering to match realtime.
 .S. remap             VVV->V     Remap pixels.
 TS. removegrain       V->V       Remove grain.
 T.. removelogo        V->V       Remove a TV logo based on a mask image.
 ... repeatfields      V->V       Hard repeat fields based on MPEG repeat field flag.
 ... reverse           V->V       Reverse a clip.
 TSC rgbashift         V->V       Shift RGBA.
 TSC roberts           V->V       Apply roberts cross operator.
 TSC rotate            V->V       Rotate the input image.
 T.. sab               V->V       Apply shape adaptive blur.
 ..C scale             V->V       Scale the input video size and/or convert the image format.
 ..C scale2ref         VV->VV     Scale the input video size and/or convert the image format to the given reference.
 ... scdet             V->V       Detect video scene change
 TSC scharr            V->V       Apply scharr operator.
 TSC scroll            V->V       Scroll input video.
 ... segment           V->N       Segment video stream.
 ... select            V->N       Select video frames to pass in output.
 TS. selectivecolor    V->V       Apply CMYK adjustments to specific color ranges.
 ... sendcmd           V->V       Send commands to filters.
 ... separatefields    V->V       Split input video frames into fields.
 ... setdar            V->V       Set the frame display aspect ratio.
 ... setfield          V->V       Force field for the output video frame.
 ... setparams         V->V       Force field, or color property for the output video frame.
 ... setpts            V->V       Set PTS for the output video frame.
 ... setrange          V->V       Force color range for the output video frame.
 ... setsar            V->V       Set the pixel sample aspect ratio.
 ... settb             V->V       Set timebase for the video output link.
 TSC shear             V->V       Shear transform the input image.
 ... showinfo          V->V       Show textual information for each video frame.
 ... showpalette       V->V       Display frame palette.
 T.. shuffleframes     V->V       Shuffle video frames.
 TS. shufflepixels     V->V       Shuffle video pixels.
 T.. shuffleplanes     V->V       Shuffle video planes.
 T.. sidedata          V->V       Manipulate video frame side data.
 .S. signalstats       V->V       Generate statistics from video analysis.
 ... signature         N->V       Calculate the MPEG-7 video signature
 T.. smartblur         V->V       Blur the input video without impacting the outlines.
 TSC sobel             V->V       Apply sobel operator.
 ... split             V->N       Pass on the input to N video outputs.
 T.C spp               V->V       Apply a simple post processing filter.
 ... sr                V->V       Apply DNN-based image super resolution to the input.
 TS. ssim              VV->V      Calculate the SSIM between two video streams.
 .S. stereo3d          V->V       Convert video stereoscopic 3D view.
 ..C streamselect      N->N       Select video streams
 ... subtitles         V->V       Render text subtitles onto input video using the libass library.
 .S. super2xsai        V->V       Scale the input by 2x using the Super2xSaI pixel art algorithm.
 T.C swaprect          V->V       Swap 2 rectangular objects in video.
 T.. swapuv            V->V       Swap U and V components.
 TSC tblend            V->V       Blend successive frames.
 ... telecine          V->V       Apply a telecine pattern.
 ... thistogram        V->V       Compute and draw a temporal histogram.
 TSC threshold         VVVV->V    Threshold first video stream using other video streams.
 T.. thumbnail         V->V       Select the most representative frame in a given sequence of consecutive frames.
 ... tile              V->V       Tile several successive frames together.
 ... tinterlace        V->V       Perform temporal field interlacing.
 TSC tlut2             V->V       Compute and apply a lookup table from two successive frames.
 TSC tmedian           V->V       Pick median pixels from successive frames.
 T.. tmidequalizer     V->V       Apply Temporal Midway Equalization.
 TSC tmix              V->V       Mix successive video frames.
 .S. tonemap           V->V       Conversion to/from different dynamic ranges.
 ... tpad              V->V       Temporarily pad video frames.
 .S. transpose         V->V       Transpose input video.
 ... trim              V->V       Pick one continuous section from the input, drop the rest.
 TS. unpremultiply     N->V       UnPreMultiply first stream with first plane of second stream.
 TS. unsharp           V->V       Sharpen or blur the input video.
 ... untile            V->V       Untile a frame into a sequence of frames.
 .SC v360              V->V       Convert 360 projection of video.
 T.. vaguedenoiser     V->V       Apply a Wavelet based Denoiser.
 TSC varblur           VV->V      Apply Variable Blur filter.
 ... vectorscope       V->V       Video vectorscope.
 T.. vflip             V->V       Flip the input video vertically.
 ... vfrdet            V->V       Variable frame rate detect filter.
 TSC vibrance          V->V       Boost or alter saturation.
 ... vidstabdetect     V->V       Extract relative transformations, pass 1 of 2 for stabilization (see vidstabtransform for pass 2).
 ... vidstabtransform  V->V       Transform the frames, pass 2 of 2 for stabilization (see vidstabdetect for pass 1).
 TS. vif               VV->V      Calculate the VIF between two video streams.
 T.. vignette          V->V       Make or reverse a vignette effect.
 ... vmafmotion        V->V       Calculate the VMAF Motion score.
 .S. vstack            N->V       Stack video inputs vertically.
 TSC w3fdif            V->V       Apply Martin Weston three field deinterlace.
 .S. waveform          V->V       Video waveform monitor.
 .S. weave             V->V       Weave input video fields into frames.
 .S. xbr               V->V       Scale the input using xBR algorithm.
 TS. xcorrelate        VV->V      Cross-correlate first video stream with second video stream.
 .S. xfade             VV->V      Cross fade one video with another video.
 TSC xmedian           N->V       Pick median pixels from several video inputs.
 .S. xstack            N->V       Stack video inputs into custom layout.
 TS. yadif             V->V       Deinterlace the input image.
 TSC yaepblur          V->V       Yet another edge preserving blur filter.
 ... zoompan           V->V       Apply Zoom & Pan effect.
 ..C zscale            V->V       Apply resizing, colorspace and bit depth conversion.
 ... allrgb            |->V       Generate all RGB colors.
 ... allyuv            |->V       Generate all yuv colors.
 ... cellauto          |->V       Create pattern generated by an elementary cellular automaton.
 ..C color             |->V       Provide an uniformly colored input.
 ... colorspectrum     |->V       Generate colors spectrum.
 ... frei0r_src        |->V       Generate a frei0r source.
 .S. gradients         |->V       Draw a gradients.
 ... haldclutsrc       |->V       Provide an identity Hald CLUT.
 ... life              |->V       Create life.
 ... mandelbrot        |->V       Render a Mandelbrot fractal.
 ... mptestsrc         |->V       Generate various test pattern.
 ... nullsrc           |->V       Null video source, return unprocessed video frames.
 ... pal75bars         |->V       Generate PAL 75% color bars.
 ... pal100bars        |->V       Generate PAL 100% color bars.
 ... rgbtestsrc        |->V       Generate RGB test pattern.
 .S. sierpinski        |->V       Render a Sierpinski fractal.
 ... smptebars         |->V       Generate SMPTE color bars.
 ... smptehdbars       |->V       Generate SMPTE HD color bars.
 ... testsrc           |->V       Generate test pattern.
 ... testsrc2          |->V       Generate another test pattern.
 ... yuvtestsrc        |->V       Generate YUV test pattern.
 ... nullsink          V->|       Do absolutely nothing with the input video.
 ... abitscope         A->V       Convert input audio to audio bit scope video output.
 ... adrawgraph        A->V       Draw a graph using input audio metadata.
 ... agraphmonitor     A->V       Show various filtergraph stats.
 ... ahistogram        A->V       Convert input audio to histogram video output.
 ... aphasemeter       A->N       Convert input audio to phase meter video output.
 .SC avectorscope      A->V       Convert input audio to vectorscope video output.
 ..C concat            N->N       Concatenate audio and video streams.
 ... showcqt           A->V       Convert input audio to a CQT (Constant/Clamped Q Transform) spectrum video output.
 ... showfreqs         A->V       Convert input audio to a frequencies video output.
 .S. showspatial       A->V       Convert input audio to a spatial video output.
 .S. showspectrum      A->V       Convert input audio to a spectrum video output.
 .S. showspectrumpic   A->V       Convert input audio to a spectrum video output single picture.
 ... showvolume        A->V       Convert input audio volume to video output.
 ... showwaves         A->V       Convert input audio to a video output.
 ... showwavespic      A->V       Convert input audio to a video output single picture.
 ... spectrumsynth     VV->A      Convert input spectrum videos to audio output.
 ..C amovie            |->N       Read audio from a movie source.
 ..C movie             |->N       Read from a movie source.
 ... afifo             A->A       Buffer input frames and send them when they are requested.
 ... fifo              V->V       Buffer input images and send them when they are requested.
 ... abuffer           |->A       Buffer audio frames, and make them accessible to the filterchain.
 ... buffer            |->V       Buffer video frames, and make them accessible to the filterchain.
 ... abuffersink       A->|       Buffer audio frames, and make them available to the end of the filter graph.
 ... buffersink        V->|       Buffer video frames, and make them available to the end of the filter graph.


Supported file protocols:
Input:
  async
  cache
  concat
  concatf
  crypto
  data
  ffrtmpcrypt
  ffrtmphttp
  file
  ftp
  gopher
  gophers
  hls
  http
  httpproxy
  https
  mmsh
  mmst
  pipe
  rtmp
  rtmpe
  rtmps
  rtmpt
  rtmpte
  rtmpts
  rtp
  sctp
  srtp
  subfile
  tcp
  tls
  udp
  udplite
  unix
  srt
Output:
  crypto
  ffrtmpcrypt
  ffrtmphttp
  file
  ftp
  gopher
  gophers
  http
  httpproxy
  https
  icecast
  md5
  pipe
  prompeg
  rtmp
  rtmpe
  rtmps
  rtmpt
  rtmpte
  rtmpts
  rtp
  sctp
  srtp
  tee
  tcp
  tls
  udp
  udplite
  unix
  srt
