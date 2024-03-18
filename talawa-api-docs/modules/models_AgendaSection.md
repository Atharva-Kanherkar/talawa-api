[talawa-api](../README.md) / [Exports](../modules.md) / models/AgendaSection

# Module: models/AgendaSection

## Table of contents

### Interfaces

- [InterfaceAgendaSection](../interfaces/models_AgendaSection.InterfaceAgendaSection.md)

### Variables

- [AgendaSectionModel](models_AgendaSection.md#agendasectionmodel)
- [AgendaSectionSchema](models_AgendaSection.md#agendasectionschema)

## Variables

### AgendaSectionModel

• `Const` **AgendaSectionModel**: `Model`\<[`InterfaceAgendaSection`](../interfaces/models_AgendaSection.InterfaceAgendaSection.md), \{\}, \{\}\>

#### Defined in

[src/models/AgendaSection.ts:68](https://github.com/PalisadoesFoundation/talawa-api/blob/0deccac/src/models/AgendaSection.ts#L68)

___

### AgendaSectionSchema

• `Const` **AgendaSectionSchema**: `Schema`\<`Document`\<`any`, `any`, `any`\>, `Model`\<`Document`\<`any`, `any`, `any`\>, `any`, `any`\>, `undefined`, \{\}\>

This is the Mongoose schema for an agenda section.

**`Param`**

Reference to the event associated with the agenda section.

**`Param`**

Description of the agenda section.

**`Param`**

Array of agenda items associated with the agenda section.

**`Param`**

Sequence number of the agenda section.

**`Param`**

Reference to the user who created the agenda section.

**`Param`**

Date when the agenda section was created.

**`Param`**

Date when the agenda section was last updated.

#### Defined in

[src/models/AgendaSection.ts:31](https://github.com/PalisadoesFoundation/talawa-api/blob/0deccac/src/models/AgendaSection.ts#L31)
