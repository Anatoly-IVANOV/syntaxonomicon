# Syntaxonomicon: The Art of Naming in Code

Welcome to the Syntaxonomicon, a variable naming convention / guide assembled since 2000 with a focus on code readability in various languages for programming geniuses like you and me who can’t remember how clever they were a month after project went live. Clear, expressive, and intuitive coding practices independent of strong or dynamic typing.

"Syntaxonomicon" = 'syntax' +  'onomicon' (a compendium of names)

## Purpose

Syntaxonomicon emerged from a need for a consistent, cross-language variable naming convention. It aims to transcend traditionally terse but obscure naming practices by introducing a longer method built on several principles:

- type indication

## Key Features

- **Type Indication Prefixes**: Each variable type begins with a specific prefix (e.g., `int_`, `str_`, `bool_`) for immediate type recognition.
- **Function Result Suffixes**: Each function has a standardised suffix to immediately give a sense of its result (a return of a conversion, a print to the UI…)
- **Macro to Micro Scope**: Planet > continent > country > city > street
- **Nouns for variables**
- **Verbs for functions**
- **No Dashes**: Compatible with languages like JavaScript, PHP, Python, Rust, and Swift.

## Naming Conventions

- `variables` → TitleCase instead of widely used camelCase
- `functions` → all lower case and underscore separators

### Variables – All Languages

- `CONSTANT_NAME`

- `int_IntegerVariableName`

- `flt_FloatVariableName`

- `str_StringVariableName`

- `bool_BooleanVariableName`

- `arr_ArrayName`

- `obj_ObjectName`

### Variables – JavaScript

- `obj_RegexName` → JavaScript Regex patterns… which are objects

- `dom_ObjectName` → JavaScript DOM objects

- `obj_event_ObjectName` → JavaScript eventListener objects

- `obj_obs_ObjectName` →	JavaScript observer objects

- `obj_err_ObjectName` → JavaScript error objects (from try/catch, for example)

- `mod_loc_ObjectName` →	JavaScript modules’ `import as` objects local to the application, not from public NPMs

- `mod_com_ObjectName` → JavaScript modules’ `import as` objects from modules common to several application or from public NPMs

### Variables – C++, PHP

- `mix_MixedTypeName` → the mixed oddball

- `class_ClassName`

- `class_inst_ClassInstanceName`

- `resource_stream_ResourceObjectWithStreamCharacteristics` → PHP low-level stuff like old MySQL connections (no longer used) or still relevant `fopen()` wrapper of the C `fopen()` function

### Functions

#### Verbs

- `verb_to_describe_what_a_function_does`

#### Suffixes

append to `verb_to_describe_what_a_function_does`, depending on its intent:

`_get` → get some value or function and return
`_conv` → process into something and return
`_bool` → to check whether something is true or not by passing into a function
`_set` → set a new variable somewhere
`_print` → print out to Console / HTML / CSS / GUI-layer
`_iife` → to more easily trace IIFEs

## Examples


## Contributing

The world of coding is ever-evolving, and so is Syntaxonomicon. Share your insights, suggest improvements, or extend these conventions to other programming languages and paradigms.
