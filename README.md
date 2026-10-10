namespace ConcatenationTask
{
    internal class Program
    {
        static void Main(string[] args)
        {
            string FirstName;
            Console.Write("Enter first name: ");
            FirstName = Console.ReadLine();
            Console.WriteLine("Last name");
            string LastName = Console.ReadLine();
            Console.WriteLine("whats age ");
            int age = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Hello " + FirstName +" "+ LastName + " you are " + age + " years old");
           
            Console.WriteLine(FirstName);
            // save and commit your program
            // add evidence of the test input and your own input running the program
