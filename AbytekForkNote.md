
We modified slang-rhi (https://github.com/shader-slang/slang-rhi -> https://github.com/Abytek/slang-rhi) to expose:
- ABYTEK_SLANG_DXCOMPILER_DLL_FILE
- ABYTEK_SLANG_DXIL_DLL_FILE

Added ABYTEK_SLANG_ENABLE_BUILTIN_SHADER_MODULE_TIMESTAMP_CHECKING (default = ON) to prevent slang from automatically re-compile slang module in debug build.