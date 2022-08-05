# 3.Adittion_of_two_numbers_using_input_method
# using System;
# using System.Collections.Generic;
# using System.Linq;
# using System.Text;
# using System.Threading.Tasks;
# 
# namespace _3.addition
# {
#     class Program
#     {
#         public void ADD(int a,int b)
#         {
#             int c=a+b;
#             Console.WriteLine("sum of {0} and {1} is {2} :- ",a, b, c);
#         }
#         static void Main(string[] args)
#         {
#             int a, b;
#             Console.WriteLine("enter the first numbers ");
#             a = Convert.ToInt32(Console.ReadLine());
#             Console.WriteLine("enter the second numbers ");
#             b = Convert.ToInt32(Console.ReadLine());
#             Program obj = new Program();
#             obj.ADD(a,b);
# 
# 
#          }
#      }
# }
