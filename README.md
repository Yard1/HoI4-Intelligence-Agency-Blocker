# Intelligence Agency Blocker modding utility by Yard1 (HoI4 Modding Coop resource).

Hearts of Iron 4 modding resource, allowing to block the creation of La Resistance Intelligence Agencies unless conditions are met.

Just drag and drop everything to your folder and change the `can_create_intelligence_agency` scripted trigger in `common/scripted_triggers/intelligence_agency_blocker_trigger.txt` as you desire. Will block both player (by making the button unclickable) and AI (by an AI strategy reducing the number of factories AI can use for intelligence way below 0). Will not block `create_intelligence_agency = yes` effect.

You may want to make copies of `localisation/intelligence_agency_blocker_l_english.yml` for other languages your mod supports.

Feel free to use in your mods, but give credits to Yard1 (both in code, with comments; and on your download page).