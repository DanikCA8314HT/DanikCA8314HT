Program days3a;

Uses Crt;

Var i: integer;

Begin

ClrScr;

writeln ('Vvedute chuslo ot 1 do 7 ');

read (i);

case i of

1: writeln (' -Ponedelnik');

2: writeln (' -Vtornik');

3: writeln (' -Sreda');

4: writeln (' -Chetverg');

5: writeln (' -Pyatnica');

6: writeln (' -Sybbota');

7: writeln (' -Voskresenie');

Else writeln (' -Takogo dnya nedeli net');

End;

Readkey;

end.
