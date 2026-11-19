MEMORA Sinhala Web App — යාවත්කාලීන සංස්කරණය

ස්ථාපනය / ආරම්භය
1. ZIP එක Extract කරන්න.
2. MEMORA_Web_App ෆෝල්ඩරය HTTPS hosting සේවාවකට (උදා: Netlify Drop) upload කරන්න.
3. Android Chrome තුළ URL එක විවෘත කර Install App තෝරන්න.
4. Trial කාලය මෙම browser/device එකේ පළමු වරට app එක ආරම්භ කරන විට පටන් ගනී.

Trial සහ Activation
- පළමු ආරම්භයේ සිට පැය 168ක් (දින 7ක්) Trial. Home හි ඉතිරි දින පෙන්වයි.
- කාලය අවසන් වූ විට සියලු අන්තර්ගත පිටු Lock වේ. Activation Key තිරය පමණක් විවෘත වේ.
- Key: RDK-PPPP-MMMM-DU-CCCC
- CCCC = (PPPP × 7 + MMMM × 13 + D × 29 + 4317) % 10000
- 1M = සක්‍රිය කළ දිනයේ සිට මාස 1; 1Y = වසර 1. කාලය අවසන් වූ විට නැවත Lock වේ.
- වැරදි Key සඳහා පෙන්වන්නේ “Key එක වැරදියි” පමණි.
- Lock වූ විට IndexedDB දත්ත මකා නොදමයි.

සීමාවන් සහ ආරක්ෂාව
- PWA බ්‍රවුසරවල Install event එක සියල්ලේම විශ්වාසදායක නොවන නිසා Trial ගණනය පළමු app launch එකෙන් අරඹයි.
- මෙම offline client-side checksum සූත්‍රය රහස්‍ය/cryptographic ආරක්ෂාවක් නොවේ. පරිශීලකයාට කේතය හෝ browser storage වෙනස් කළ හැකි බැවින් වාණිජ නිෂ්පාදනයකට server/private-key මත පදනම් වූ signed license ක්‍රමයක් අවශ්‍යය.
- Browser data clear කළහොත් Trial තත්ත්වය reset විය හැකිය.
- Alarm / Reminder පහසුකම ඇතුළත් කර නැත.
- දත්ත IndexedDB තුළ එම browser/device එකේම පවතී. Backup නිතර ගන්න.

මුල් පිටුවේ නව දෘශ්‍ය සැලසුම
- ඉහළින් මුල් පිටුව සහ සැකසුම් බොත්තම් දෙක පමණි. පහළ navigation bar එකක් නැත.
- මැද MEMORA ලාංඡනය, දිනය සහ Trial countdown පෙන්වයි.
- ප්‍රධාන කාඩ්පත් හතර: මගේ පාඩම්, අද සමාලෝචනය, අලුත් පාඩමක්, ප්‍රශ්න පත්‍ර.
- පහළින් දෛනික සමාලෝචන ප්‍රගතිය දත්ත අනුව ගණනය කර පෙන්වයි; පෙරනිමි ව්‍යාජ ඉලක්ක අගයන් භාවිත නොකරයි.
