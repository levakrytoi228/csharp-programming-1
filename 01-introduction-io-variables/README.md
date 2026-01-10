# Theme 1: Introduction, Variables, Input and Output

This folder contains assignments related to basic C# syntax,
variables, and console input/output.


```csharp
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

/*
Esittele ja anna alkuarvot muuttujille, joihin pitäisi tallentaa seuraavat tiedot:

piin likiarvo
lähiosoite
henkilötunnus
nimesi ensimmäinen kirjain
lämpötila yhden desimaalin tarkkuudella

Tulosta arvot muuttujista allekkain käyttäen sekä Console.WriteLine(), että Console.Write()-komentoja.
Ohjelman pitää tulostaa seuraavat tiedot:

3.14159
Munkkikuja 3
121299A1234
S
-12.4
*/

namespace Projekti
{
    class Program
    {
        static void Main()
        {
            double dPi = 3.14159;
            Console.WriteLine(dPi);
            string sMunkkikuja = "Munkkikuja 3";
            Console.WriteLine(sMunkkikuja);
            string sHenkilotunnus = "121299A1234";
            Console.WriteLine(sHenkilotunnus);
            char cKirjain = 'S';
            Console.WriteLine(cKirjain);
            double dLampotila = -12.4;
            Console.WriteLine(dLampotila);
        }
    }
}
