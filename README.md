V8 Sandbox escape/bypass/violation collection
=============================================
A collection of links related to V8 sandbox VR and exploitation

## Contents

- [IssueTracker](#issuetracker)
- [Articles](#articles)
- [Papers & Slides](#papers)

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

[2024: "issue id: 331042197, V8 sandbox violation in v8::internal::Scavenger::IterateAndScavengePromotedObject](https://issuetracker.google.com/issues/331042197)

[2024: "issue id: 330922416, V8 sandbox violation in v8::internal::ArrayBufferExtension::backing_store](https://issuetracker.google.com/issues/330922416)

[2024: "issue id: 331036491, V8 sandbox violation in icu_73::Locale::getBaseName](https://issuetracker.google.com/issues/331036491)

[2024: "issue id: 330096629, V8 sandbox violation in icu_73::RelativeDateTimeFormatter::getFormatStyle](https://issuetracker.google.com/issues/330096629)

[2024: "issue id: 331241020, V8 sandbox violation and memory corruption due to buffer overflow in compiler](https://issuetracker.google.com/issues/331241020)

[2024: "issue id: 331883947, V8 sandbox violation in v8::internal::Managed<icu_73::Locale>::GetSharedPtrPtr](https://issuetracker.google.com/issues/331883947)

[2024: "issue id: 331837303, V8 sandbox violation in v8::internal::maglev::MaglevGraphBuilder::TryBuildInlinedAllocatedContext](https://issuetracker.google.com/issues/331837303)

[2024: "issue id: 331042216, V8 sandbox violation in v8::internal::LazyCreateDateIntervalFormat](https://issuetracker.google.com/issues/331042216)

[2024: "issue id: 333065495, V8 sandbox violation in v8::internal::MemoryChunkMetadata::heap](https://issuetracker.google.com/issues/333065495)

[2024: "issue id: 329920544, V8 sandbox violation in v8::internal::Managed<icu_73::number::LocalizedNumberFormatter>::GetSharedPtrPtr](https://issuetracker.google.com/issues/329920544)

[2024: "issue id: 330800450, V8 sandbox violation in unsigned long v8::base::AsAtomicImpl<long>::Relaxed_Load<unsigned long>](https://issuetracker.google.com/issues/330800450)

## Articles

## Papers & Slides
