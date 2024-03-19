﻿- Do NOT Translate anything in curly ({}) braces inside strings. These are used for formatting.
- Do not translate FontFamily, this is the font used by the locale
- SupportedNameBlock should be empty for latin alphabets. Reference here: https://docs.microsoft.com/en-us/dotnet/standard/base-types/character-classes-in-regular-expressions#supported-named-blocks
- MergedCollectionPrefix is used in path generation so should not be translated (depending on the type of language)
- MergeCompressModPrefix is used in path generation so should not be translated (depending on the type of language)