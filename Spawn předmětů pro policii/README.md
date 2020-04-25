## Frakce
Jedná se o sadu propů pro __Sheriff Department__, kterou budou moci spawnout.
<a href="https://cdn.discordapp.com/attachments/696442851848093756/703617464516476938/20200305232016_1.jpg" target="_blank"><img alt="doorlock" src="https://cdn.discordapp.com/attachments/696442851848093756/703617464516476938/20200305232016_1.jpg"></a>
<a href="https://cdn.discordapp.com/attachments/696442851848093756/703617466848509962/20200305232031_1.jpg" target="_blank"><img alt="doorlock" src="https://cdn.discordapp.com/attachments/696442851848093756/703617466848509962/20200305232031_1.jpg"></a>

## Použití
Text z __Citizen-CreateThread.lua__ zkopírujte do své složky s frakcí **esx_policejob/client/main.lua**, vyhledejte si **elseif data.current.value == 'object_spawner' then** a vložte text dle následujícího obrázku. Pozor, abyste neměli některé předměty 2x :). Záměrně byl odstraněn překážkový pás, který PD často spawnovali a již je nešlo despawnout.

<a href="https://cdn.discordapp.com/attachments/696442851848093756/703622596205478058/5678534245285.png" target="_blank"><img alt="doorlock" src="https://cdn.discordapp.com/attachments/696442851848093756/703622596205478058/5678534245285.png"></a>

Text z **function.lua** zkopírujte do své složky s frakcí **esx_policejob/client/main.lua**, vyhledejte si řádek **local trackedEntities = {** a vložte jej jako je to na následujícím obrázku.

<a href="https://cdn.discordapp.com/attachments/696442851848093756/703624154968096879/335428727.png" target="_blank"><img alt="doorlock" src="https://cdn.discordapp.com/attachments/696442851848093756/703624154968096879/335428727.png"></a>

Text z **locales.lua** zkopírujte do své složky s překladem, kterým používáte **esx_policejob/locales**, do sekce **Traffic interaction**.

<a href="https://cdn.discordapp.com/attachments/703626453232910416/703626479346647060/47577.png" target="_blank"><img alt="doorlock" src="https://cdn.discordapp.com/attachments/703626453232910416/703626479346647060/47577.png"></a>

## Obsah
- [x] Nové předměty ke spawnu.
- [x] Český překlad s omezenou diakritikou.
- [ ] Barrierový pás.
