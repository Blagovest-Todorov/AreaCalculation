# AreaCalculation
how to calulate rectangle or triangle area

    class Program
    {
        static void Main(string[] args)

        {
            Thread.CurrentThread.CurrentCulture =
                CultureInfo.InvariantCulture;
            Console.WriteLine("This Program calculates the area of a rectangle");

            Console.WriteLine("Enter a and b( for rectangle) or a and h  (for an triangle)");
            int a = int.Parse(Console.ReadLine());
            int b = int.Parse(Console.ReadLine());

            Console.WriteLine("Enter 1 for a rectangle and 2 for a triangle: ");
            int choice = int.Parse(Console.ReadLine());
            double area = (double)(a * b) / choice;
            Console.WriteLine("The area  of your  figure is {0}", area);
        }
    }
}
