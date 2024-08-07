V8 Sandbox escape/bypass/violation and VR collection
====================================================
A collection of links related to V8 sandbox VR and exploitation

## Contents

- [IssueTracker](#issuetracker)
- [Articles](#articles)
- [Papers & Slides](#papers--slides)

## IssueTracker

[2024: "issue id: 327732554, V8 sandbox violation due to signed comparison of (untrusted) string length against buffer size"](https://issuetracker.google.com/issues/327732554)

[2024: "issue id: 326086002, Sandbox violations due to (exhaustive) switches over enums when the code after the switch has UB"](https://issuetracker.google.com/issues/326086002)

[2024: "issue id: 327732554, V8 sandbox violation in v8::internal::Builtins::code"](https://issuetracker.google.com/issues/327732554)

[2024: "issue id: 328692018, V8 sandbox violation in v8::bigint::Digits::read_4byte_aligned"](https://issuetracker.google.com/issues/328692018)

[2024: "issue id: 328858270, V8 sandbox violation in v8::internal::GetBailoutReason"](https://issuetracker.google.com/issues/328858270)

[2024: "issue id: 332475841, V8 sandbox violation in v8::internal::ElementsKindToString"](https://issuetracker.google.com/issues/332475841)

[2024: "issue id: 41487854, V8 sandbox violation in Builtins_StarWideHandler"](https://issuetracker.google.com/issues/41487854)

[2024: "issue id: 323736727, V8 sandbox violation in Builtins_DeoptimizationEntry_Eager"](https://issuetracker.google.com/issues/323736727)

[2024: "issue id: 323694399, V8 sandbox violation in Builtins_DeoptimizationEntry_Eager"](https://issuetracker.google.com/issues/323694399)

[2024: "issue id: 323696394, V8 sandbox violation in Builtins_DeoptimizationEntry_Eager"](https://issuetracker.google.com/issues/323696394)

[2024: "issue id: 323690010, V8 sandbox violation in Builtins_DeoptimizationEntry_Eager"](https://issuetracker.google.com/issues/323690010)

[2024: "issue id: 327550517, V8 sandbox violation in v8::internal::ArrayBufferSweeper::Detach"](https://issuetracker.google.com/issues/327550517)

[2024: "issue id: 324343442, V8 sandbox violation in v8::internal::SemiSpace::FixPagesFlags"](https://issuetracker.google.com/issues/324343442)

[2024: "issue id: 324482838, V8 sandbox violation in v8::internal::maglev::MaglevGraphBuilder::BuildAllocateFastObject"](https://issuetracker.google.com/issues/324482838)

[2024: "issue id: 326109866, Use-after-poison in v8::internal::compiler::MapData::instance_type"](https://issuetracker.google.com/issues/326109866)

[2024: "issue id: 327719160, V8 sandbox violation in v8::internal::MarkCompactCollector::ProcessMarkingWorklist"](https://issuetracker.google.com/issues/327719160)

[2024: "issue id: 327827222, V8 sandbox violation in v8::internal::ConcurrentMarking::RunMajor"](https://issuetracker.google.com/issues/327827222)

[2024: "issue id: 329425726, V8 sandbox violation in v8::internal::Scavenger::IterateAndScavengePromotedObject"](https://issuetracker.google.com/issues/329425726)

[2024: "issue id: 329886545, V8 sandbox violation in v8::internal::JSFunction::CalculateExpectedNofProperties"](https://issuetracker.google.com/issues/329886545)

[2024: "issue id: 330219140, V8 sandbox violation in unsigned int v8::base::AsAtomicImpl<int>::Relaxed_Load<unsigned int>"](https://issuetracker.google.com/issues/330219140)

[2024: "issue id: 330385840, V8 sandbox violation in v8::internal::Code::kind"](https://issuetracker.google.com/issues/330385840)

[2024: "issue id: 330404819, V8 Sandbox escape via regexp"](https://issuetracker.google.com/issues/330404819)

[2024: "issue id: 329781445, V8 sandbox violation in v8::internal::Scavenger::IterateAndScavengePromotedObject"](https://issuetracker.google.com/issues/329781445)

[2024: "issue id: 330563095, WebCodecs VideoFrame Race Condition UAF Write to RCE" by Seunghyun Lee(@0x10n)](https://issuetracker.google.com/issues/330563095) [Pwn2Own 2024] 

[2024: "issue id: 331042197, V8 sandbox violation in v8::internal::Scavenger::IterateAndScavengePromotedObject"](https://issuetracker.google.com/issues/331042197)

[2024: "issue id: 330922416, V8 sandbox violation in v8::internal::ArrayBufferExtension::backing_store"](https://issuetracker.google.com/issues/330922416)

[2024: "issue id: 331036491, V8 sandbox violation in icu_73::Locale::getBaseName"](https://issuetracker.google.com/issues/331036491)

[2024: "issue id: 330096629, V8 sandbox violation in icu_73::RelativeDateTimeFormatter::getFormatStyle"](https://issuetracker.google.com/issues/330096629)

[2024: "issue id: 331241020, V8 sandbox violation and memory corruption due to buffer overflow in compiler"](https://issuetracker.google.com/issues/331241020)

[2024: "issue id: 331883947, V8 sandbox violation in v8::internal::Managed<icu_73::Locale>::GetSharedPtrPtr"](https://issuetracker.google.com/issues/331883947)

[2024: "issue id: 331837303, V8 sandbox violation in v8::internal::maglev::MaglevGraphBuilder::TryBuildInlinedAllocatedContext"](https://issuetracker.google.com/issues/331837303)

[2024: "issue id: 331042216, V8 sandbox violation in v8::internal::LazyCreateDateIntervalFormat"](https://issuetracker.google.com/issues/331042216)

[2024: "issue id: 333065495, V8 sandbox violation in v8::internal::MemoryChunkMetadata::heap"](https://issuetracker.google.com/issues/333065495)

[2024: "issue id: 329920544, V8 sandbox violation in v8::internal::Managed<icu_73::number::LocalizedNumberFormatter>::GetSharedPtrPtr"](https://issuetracker.google.com/issues/329920544)

[2024: "issue id: 330800450, V8 sandbox violation in unsigned long v8::base::AsAtomicImpl<long>::Relaxed_Load<unsigned long>"](https://issuetracker.google.com/issues/330800450)

[2024: "issue id: 335763881, V8 sandbox violation in v8::internal::TranslatedState::CreateNextTranslatedValue"](https://issuetracker.google.com/issues/335763881)

[2024: "issue id: 335544065, V8 sandbox violation in Builtins_DeoptimizationEntry_Eager"](https://issuetracker.google.com/issues/335544065)

[2024: "issue id: 335322609, V8 sandbox violation in v8::internal::maglev::CapturedObject::set"](https://issuetracker.google.com/issues/335322609)

[2024: "issue id: 335810507, V8 sandbox violation in v8::internal::ToLatin1Lower"](https://issuetracker.google.com/issues/335810507)

[2024: "issue id: 337094992, V8 sandbox violation in v8::internal::ArrayBufferExtension::backing_store"](https://issuetracker.google.com/issues/337094992)

[2024: "issue id: 336655186, V8 sandbox violation in v8::internal::Scavenger::IterateAndScavengePromotedObject"](https://issuetracker.google.com/issues/336655186)

[2024: "issue id: 333829668, V8 sandbox violation in v8::base::Flags<v8::internal::MemoryChunk::Flag, unsigned long, unsigned long>::"](https://issuetracker.google.com/issues/333829668)

[2024: "issue id: 327473161, V8 sandbox violation in v8::internal::TranslatedState::CreateNextTranslatedValue"](https://issuetracker.google.com/issues/327473161)


## Articles

[2023: "Use Native Pointer of Function to Bypass The Latest Chrome v8 Sandbox (exp of issue1378239)"](https://medium.com/@numencyberlabs/use-native-pointer-of-function-to-bypass-the-latest-chrome-v8-sandbox-exp-of-issue1378239-251d9c5b0d14)

[2023: "Use Wasm to Bypass Latest Chrome v8sbx Again"](https://medium.com/@numencyberlabs/use-wasm-to-bypass-latest-chrome-v8sbx-again-639c4c05b157)

[2023: "Code Execution in Chromium’s V8 Heap Sandbox"](https://anvbis.au/posts/code-execution-in-chromiums-v8-heap-sandbox/)

[2023: "Abusing Liftoff assembly and efficiently escaping from sbx(@r3tr074)"](https://retr0.zip/blog/abusing-Liftoff-assembly-and-efficiently-escaping-from-sbx.html)

[2024: "A Deep Dive into V8 Sandbox Escape Technique Used in In-The-Wild Exploit"](https://blog.theori.io/a-deep-dive-into-v8-sandbox-escape-technique-used-in-in-the-wild-exploit-d5dcf30681d4)

[2024: "CVE-2024-2887: A Pwn2Own Winning Bug in Google Chrome"](https://www.zerodayinitiative.com/blog/2024/5/2/cve-2024-2887-a-pwn2own-winning-bug-in-google-chrome)

## Papers & Slides

[2024: "The V8 Heap Sandbox(Samuel Groß, @5aelo) - OffensiveCon 2024"](https://saelo.github.io/presentations/offensivecon_24_the_v8_heap_sandbox.pdf)

[2024: "A Chrome/Edge RCE via V8 WASM Type Confusion by Manfred Paul(@_manfp) Pwn2Own Vancouver 2024"](https://issues.chromium.org/action/issues/330575498/attachments/54838004?download=false)

[2024: "Google Chrome Renderer Only RCE by Seunghyun Lee (@0x10n) Pwn2Own Vancouver 2024"](https://issues.chromium.org/action/issues/330575498/attachments/54838004?download=false)


