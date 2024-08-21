V8 Sandbox escape/bypass/violation and VR collection
====================================================
A collection of links related to V8 sandbox VR and exploitation

## Contents

- [IssueTracker](#issuetracker)
- [Articles](#articles)
- [Papers & Slides](#papers--slides)
- [Design documents](#design-documents)

## IssueTracker

[2023: "issue id: 40940619, V8 Sandbox escape due to type tags in ExternalPointerTable being too coarse for Embedder Objects"](https://issuetracker.google.com/issues/40940619)

[2024: "issue id: 42204606, Mitigate sandbox escapes in RegExp"](https://issuetracker.google.com/issues/42204606)

[2024: "issue id: 336507783, V8 Sandbox: Prevent Wasm-based sandbox escapes "](https://issuetracker.google.com/issues/336507783)

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

[2024: "issue id: 334120897, V8 Sandbox Bypass: wasm function signature confusion leading to out of sandbox arbitrary read/write "](https://issuetracker.google.com/issues/334120897)

[2024: "issue id: 336648007, V8 sandbox violation in v8::internal::maglev::CapturedObject::set"](https://issuetracker.google.com/issues/336648007)

[2024: "issue id: 343407073, V8 Sandbox Bypass: control-flow hijacking via WASM Table Indirect call"](https://issuetracker.google.com/issues/343407073)[Edouard Bochin (@le_douds) and Tao Yan (@Ga1ois)]

[2024: "issue id: 339141292, V8 sandbox violation in Builtins_JSToJSWrapper"](https://issuetracker.google.com/issues/339141292)

[2024: "issue id: 339310133, V8 sandbox violation in v8::internal::maglev::CapturedObject::set"](https://issuetracker.google.com/issues/339310133)

[2024: "issue id: 339517309, V8 sandbox violation in v8::internal::maglev::CapturedObject::set"](https://issuetracker.google.com/issues/339517309)

[2024: "issue id: 338342089, V8 sandbox violation in v8::internal::wasm::name "](https://issuetracker.google.com/issues/338342089)


## Articles

[2022: "Code Execution in Chromium’s V8 Heap Sandbox"](https://anvbis.au/posts/code-execution-in-chromiums-v8-heap-sandbox/)

[2022: "KITCTFCTF 2022 V8 Heap Sandbox Escape"](https://ju256.rip/posts/kitctfctf22-date/)

[2022: "Memory Hole: Breaking V8 Heap Sandbox"](https://mem2019.github.io/jekyll/update/2022/02/06/DiceCTF-Memory-Hole.html)[Dice CTF]

[2023: "Use Native Pointer of Function to Bypass The Latest Chrome v8 Sandbox (exp of issue1378239)"](https://medium.com/@numencyberlabs/use-native-pointer-of-function-to-bypass-the-latest-chrome-v8-sandbox-exp-of-issue1378239-251d9c5b0d14)

[2023: "Use Wasm to Bypass Latest Chrome v8sbx Again"](https://medium.com/@numencyberlabs/use-wasm-to-bypass-latest-chrome-v8sbx-again-639c4c05b157)

[2023: "Exploiting Zenbleed from Chrome"](https://vu.ls/blog/exploiting-zenbleed-from-chrome/)

[2023: "Exploring Historical V8 Heap Sandbox Escapes I"](https://anvbis.au/posts/exploring-historical-v8-heap-sandbox-escapes-i/)

[2023: "Abusing Liftoff assembly and efficiently escaping from sbx(@r3tr074)"](https://retr0.zip/blog/abusing-Liftoff-assembly-and-efficiently-escaping-from-sbx.html)

[2024: "The V8 Sandbox"](https://v8.dev/blog/sandbox)

[2024: "From object transition to RCE in the Chrome renderer"](https://github.blog/security/vulnerability-research/from-object-transition-to-rce-in-the-chrome-renderer/)

[2024: "Attack of the clones: Getting RCE in Chrome’s renderer with duplicate object properties"](https://github.blog/security/vulnerability-research/attack-of-the-clones-getting-rce-in-chromes-renderer-with-duplicate-object-properties/)

[2024: "A Deep Dive into V8 Sandbox Escape Technique Used in In-The-Wild Exploit"](https://blog.theori.io/a-deep-dive-into-v8-sandbox-escape-technique-used-in-in-the-wild-exploit-d5dcf30681d4)

[2024: "CVE-2024-2887: A Pwn2Own Winning Bug in Google Chrome"](https://www.zerodayinitiative.com/blog/2024/5/2/cve-2024-2887-a-pwn2own-winning-bug-in-google-chrome)

[2024: "Breaking V8 Sandbox with Trusted Pointer Table"](https://mem2019.github.io/jekyll/update/2024/07/14/HITCON.html)[HITCON CTF 2024]

## Papers & Slides

[2022: "Sandboxing V8(Samuel Groß, @5aelo)"](https://docs.google.com/presentation/d/1iDWDHuAZ8ee-dRF5Lkf0nwO2mkLdZG_YJEP1yPvJ09E/edit)

[2023: "Modern chrome exploit chain development"](https://powerofcommunity.net/poc2023/Avboy1337.pdf)[POC2023 - @numencyber]

[2024: "The V8 Heap Sandbox(Samuel Groß, @5aelo)"](https://saelo.github.io/presentations/offensivecon_24_the_v8_heap_sandbox.pdf)[OffensiveCon 2024]

[2024: "A Chrome/Edge RCE via V8 WASM Type Confusion by Manfred Paul(@_manfp)"](https://issues.chromium.org/action/issues/330575498/attachments/54838004?download=false)[Pwn2Own Vancouver 2024]

[2024: "Google Chrome Renderer Only RCE by Seunghyun Lee (@0x10n)"](https://issues.chromium.org/action/issues/330575498/attachments/54838004?download=false)[Pwn2Own Vancouver 2024]

[2024: "Evolution of the protections of the V8 JSE"](https://www.sstic.org/2024/presentation/evolution_des_protections_du_moteur_javascript_v8/)[[slides](https://www.sstic.org/media/SSTIC2024/SSTIC-actes/evolution_des_protections_du_moteur_javascript_v8/SSTIC2024-Slides-evolution_des_protections_du_moteur_javascript_v8-jolivet.pdf)][[Full Article](https://www.sstic.org/media/SSTIC2024/SSTIC-actes/evolution_des_protections_du_moteur_javascript_v8/SSTIC2024-Article-evolution_des_protections_du_moteur_javascript_v8-jolivet.pdf)][SSTIC2024]

[2024: "From the Vulnerability to the Victory: A Chrome Renderer 1-Day Exploit’s Journey to v8CTF Glory"](https://kaist-hacking.github.io/pubs/2024/lee:v8-ctf-slides.pdf)[TyphoonCon 2024]

[2024: "TIKTAG: Breaking ARM’s Memory Tagging Extension with Speculative Execution"](https://arxiv.org/pdf/2406.08719v1)

[2024: "Let the Cache Cache and Let the WebAssembly Assemble: Knockin' on Chrome's Shell"](https://i.blackhat.com/BH-US-24/Presentations/US24-Bochin-Let-The-Cache-Cache-and-Wednesday.pdf)[blackhat USA 2024]

[2024: "V8 Sandbox Escape Write Up - Edouard Bochin (@le_douds) and Tao Yan (@Ga1ois)"](https://issues.chromium.org/action/issues/343407073/attachments/56741064?download=false)[Pwn2Own Vancouver 2024]



## Design documents

[2019: "Compressed pointers in V8"](https://docs.google.com/document/d/10qh2-b4C5OtSg-xLwyZpEI5ZihVBPtn1xwKBbQC26yI/edit#heading=h.x1cv1fi5g42q)

[2021: "V8 Sandbox"](https://docs.google.com/document/d/1FM4fQmIhEqPG8uGp5o9A-mnPB5BOeScZYpkHjo0KKA8/edit#heading=h.xzptrog8pyxf)

[2022: "V8 Sandbox - Address Space"](https://docs.google.com/document/d/1PM4Zqmlt8ac5O8UNQfY7fOsem-6MhbsB-vjFI-9XK6w/edit#heading=h.xzptrog8pyxf)

[2022: "V8 Sandbox - Sandboxed Pointers"](https://docs.google.com/document/d/1HSap8-J3HcrZvT7-5NsbYWcjfc0BVoops5TDHZNsnko/edit#heading=h.suker1x4zgzz)

[2022: "V8 Sandbox - External Pointer Sandboxing"](https://docs.google.com/document/d/1V3sxltuFjjhp_6grGHgfqZNK57qfzGzme0QTk0IXDHk/edit#heading=h.xzptrog8pyxf)

[2022: "V8 Sandbox - Code Pointer Sandboxing"](https://docs.google.com/document/d/1CPs5PutbnmI-c5g7e_Td9CNGh5BvpLleKCqUnqmD82k/edit#heading=h.xzptrog8pyxf)

[2023: "V8 Sandbox - Glossary"](https://docs.google.com/document/d/10ZVrH2m_cbsjhZmjnWd4K5jpEHWCLourq2dulwN8elI/edit#heading=h.diogznvalour)

[2023: "V8 Sandbox - Trusted Space"](https://docs.google.com/document/d/1IrvzL4uX_Zv0k2Iakdp_q_z33bj-qlYF5IesGpXW0fM/edit#heading=h.xzptrog8pyxf)

[2024: "Multiple sandboxes aka sandbox per isolate group"](https://docs.google.com/document/d/1ja0SUpqpueNDsoYf51ydnUflZlpQknwO3h4Aw4uGAto/edit#heading=h.rhlvjpysxkfs)

[2024: "V8 Sandbox - Hardware Support"](https://docs.google.com/document/d/12MsaG6BYRB-jQWNkZiuM3bY8X2B2cAsCMLLdgErvK4c/edit#heading=h.xzptrog8pyxf)

[2024: "V8 Sandbox - Embedder Pointer Sandboxing"](https://docs.google.com/document/d/14m6CjJYaTFEmEq7czOOL5iqzMe72Owyy3PmxKdgaAms/edit#heading=h.xzptrog8pyxf)

[2024: "V8 Sandbox + Leaptiering"](https://docs.google.com/document/d/1WkyEynMluvIr0LBmrapyF7MiE8wIHFHnlP5B6FFhQuA/edit#heading=h.xzptrog8pyxf)

