# AI Agent Guide: riotplan-commands-feedback

Feedback commands for preserving deliberation in RiotPlan.

## Quick Start

```typescript
import { Command } from 'commander';
import { registerFeedbackCommands } from '@riotprompt/riotplan-commands-feedback';

const program = new Command();
registerFeedbackCommands(program);
program.parse();
```
