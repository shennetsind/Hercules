Hercules
========

Hellooooo. WIP. Commits will be later squashed

## Notes etca
* Exporting logic is forced on (hardcoded if(1) thing), need a proper way to activate it (command line arg?)
* Export format is not final
* To save memory, when (struct script_code_str)->flag.translation is set the available translations will follow up in the stack (outside of the struct memory), packet-style.
* …