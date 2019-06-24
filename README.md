# NjRat-Golden-Edition-Information-Decrypter
Decrypts whatever you need for, could be either `DNS`, `PORT` or `VN`.

# Sample Code:

- Horg
Is the encrypted `OK.H`
- Porg
Is the encrypted `OK.P`
- VNorg
Is the encrypted `OK.VN`

```csharp
using Microsoft.VisualBasic;
using System;
using System.Text;

namespace Decryptor
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.OutputEncoding = Encoding.UTF8;
            Console.WriteLine("NjRat Golden Edition Information Decrypter");
            string Horg = "बीपी29vबीपी2xlYmFpeGFyLmR1Y2tkbnविनीub3Jn";
            string Porg = "粹ताE3Nw==";
            string VNorg = "c2FpdSBrYXJhaQ==";

            string Hdec = Encoding.UTF8.GetString(Convert.FromBase64String(Strings.Replace(Strings.Replace(Strings.Replace(Strings.Replace(Strings.Replace(Horg, "विनी", "M", 1, -1, CompareMethod.Binary), "!", "=", 1, -1, CompareMethod.Binary), "蒂", "T", 1, -1, CompareMethod.Binary), "मे", "A", 1, -1, CompareMethod.Binary), "बीपी", "Z", 1, -1, CompareMethod.Binary)));
            string Pdec = Encoding.UTF8.GetString(Convert.FromBase64String(Strings.Replace(Strings.Replace(Strings.Replace(Strings.Replace(Porg, "粹", "M", 1, -1, CompareMethod.Binary), "ता", "T", 1, -1, CompareMethod.Binary), "의도", "A", 1, -1, CompareMethod.Binary), "에", "e", 1, -1, CompareMethod.Binary)));
            string VNdec = Encoding.UTF8.GetString(Convert.FromBase64String(VNorg));

            Console.WriteLine(string.Format("OK.H DEC: {0}\nOK.P DEC: {1}\nOK.VN DEC: {2}", Hdec, Pdec, VNdec));
            Console.ReadKey();
        }
    }
}

```

Enjoy ✌
