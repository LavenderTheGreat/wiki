# Pointers

Pointers are a recurring data type that refers to data at another location in the RAM (Typically the piece of the RAM with the ROM loaded into it, ``0x08000000``). Notably, they appear often around [animations](?a=formats/animations), with large arrays of them being present pointing to various animation states.

<p align="center">
    <img src="res/formats/pointer.png">
    <br>
    <i>Sonic's moveset pointers as viewed in <a href="?a=tools/hxd">HxD</a></i>.
</p>

Like the rest of Sonic Battle's data, they are written in [little endian](?a=formats/littleendian), which means byte order will appear reversed.

Pointers are also used for [LZ compressed data](?a=formats/lzcompression).