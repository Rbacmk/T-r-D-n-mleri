# T-r-D-n-mleri
 //Tip Dönüşümleri
            //Biliçsiz Dönüşüm
            
            byte a = 5;
            sbyte b = 30;
            short c = 10;
            int d = a + b + c;
            Console.WriteLine("d :"d);
            long h = d;
            Console.WriteLine("h:" + h);
            float i = h;
            Console.WriteLine("i:"+i);
            string e = "zikriye";
            char f = 'k';
            object g = e + f + d;
            Console.WriteLine("g:" + g);

            // Bilinçli Tür Dönüşümleri
            Console.WriteLine("Bilinçli tür dönüşümleri");
            int x = 4;
            byte y =(byte) x;
            Console.WriteLine("y:" + y);
