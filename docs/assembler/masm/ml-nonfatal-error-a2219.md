---
title: "ML Nonfatal Error A2219"
ms.date: "08/30/2018"
ms.custom: "error-reference"
f1_keywords: ["A2219"]
helpviewer_keywords: ["A2219"]
ms.assetid: 5ebc2f40-e47e-4f8e-b7b9-960b9cfc9f6d
---
# ML Nonfatal Error A2219

> Bad alignment for offset in unwind code

## Remarks

The operand for [&period;ALLOCSTACK](../../assembler/masm/dot-allocstack.md) and [&period;SAVEREG](../../assembler/masm/dot-savereg.md) must be a multiple of 8.  The operand for [&period;SAVEXMM128](../../assembler/masm/dot-savexmm128.md) and [&period;SETFRAME](../../assembler/masm/dot-setframe.md) must be a multiple of 16.

## See also

[ML error messages](../../assembler/masm/ml-error-messages.md)
