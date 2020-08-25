# Stas
OpenAp
      <AdditionalOptions>/utf-8 /std:c++17 %(AdditionalOptions)</AdditionalOptions>
      <DisableSpecificWarnings>4018;4221;4244;4267;4334;4715;4805;4834</DisableSpecificWarnings>
      <TreatWarningAsError>true</TreatWarningAsError>
      <PreprocessorDefinitions>_SILENCE_CXX17_CODECVT_HEADER_DEPRECATION_WARNING;_SILENCE_CXX17_OLD_ALLOCATOR_MEMBERS_DEPRECATION_WARNING;ZMQ_STATIC;NOMINMAX;WIN32;HAVE_CONFIG_H;_CRT_SECURE_NO_WARNINGS;_SCL_SECURE_NO_WARNINGS;_CONSOLE;_WIN32_WINNT=0x0601;%(PreprocessorDefinitions)</PreprocessorDefinitions>
      <PreprocessorDefinitions>_SILENCE_CXX17_CODECVT_HEADER_DEPRECATION_WARNING;_SILENCE_CXX17_OLD_ALLOCATOR_MEMBERS_DEPRECATION_WARNING;ZMQ_STATIC;NOMINMAX;WIN32;HAVE_CONFIG_H;_CRT_SECURE_NO_WARNINGS;_SCL_SECURE_NO_WARNINGS;_CONSOLE;_WIN32_WINNT=0x0601;_WIN32_IE=0x0501;WIN32_LEAN_AND_MEAN;%(PreprocessorDefinitions)</PreprocessorDefinitions>
      <AdditionalIncludeDirectories>..\..\src;..\..\src\univalue\include;..\..\src\secp256k1\include;..\..\src\leveldb\include;..\..\src\leveldb\helpers\memenv;%(AdditionalIncludeDirectories)</AdditionalIncludeDirectories>
    </ClCompile>
    <Link>
