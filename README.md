## PHB35 plugin for the Quilvyn RPG character sheet generator

The quilvyn-phb35 package bundles modules that apply additional rules from the
<a href="https://www.drivethrurpg.com/product/148008/Players-Handbook-35">v3.5
Player's Handbook</a>.

### Requirements

quilvyn-phb35 relies on the core and srd35 modules installed by the
quilvyn-core package.

### Installation

To use quilvyn-phb35, unbundle the release package into the plugins/
subdirectory within the Quilvyn installation directory, then append the
following lines to the file plugins/plugins.js:

    RULESETS['D&D v3.5'] = {
      url:'plugins/PHB35.js',
      group:'v3.5',
      require:'v3.5 (SRD only)'
    };

### Usage

Once the quilvyn-phb35 package is installed as described above, start Quilvyn
and check the box next to "D&D v3.5" from the rule sets menu in the initial
window.
