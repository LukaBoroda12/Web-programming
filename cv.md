![My photo](my_photo.jpg)
# Borodinski Luka
Software Engineer
## Summary
Engineer specializing in high-load systems and automated workflows. Focused on delivering clean, maintainable code and robust architectural solutions for web platforms.
## Contact
Mobile: +375336333379

Email: borodinski@internet.ru

Address: 14 Kuleshova St
Mogilev, Belarus

## Technical Skills
* **Languages:** С#, С++, JavaScript, Python, SQL.

* **Frameworks:** React, Node.js, Express, Django.

* **Tools:** Git, Docker, AWS, PostgreSQL.

* **Languages:** English, Russian.

### Sample code in C#:

        static Processor CreateProcessor(string model, string manufacturer, int cores, double frequency, decimal price)
        {
            Processor p = new Processor
            {
                Model = model,
                Manufacturer = manufacturer,
                Cores = cores,
                Frequency = frequency,
                Price = price
            };
            return p;
        }

        static void AddProcessorToArray(Processor processor)
        {
            Array.Resize(ref processors, processors.Length + 1);
            processors[processors.Length - 1] = processor;
        }

        static void AddProcessor()
        {
            Console.WriteLine("Добавление нового процессора");
            
            Console.Write("Модель: ");
            string model = Console.ReadLine();

            Console.Write("Производитель: ");
            string manufacturer = Console.ReadLine();

            Console.Write("Количество ядер: ");
            int cores;
            while (!int.TryParse(Console.ReadLine(), out cores) || cores <= 0)
            {
                Console.WriteLine("Введите положительное целое число");
            }

            Console.Write("Частота (ГГц): ");
            double frequency;
            while (!double.TryParse(Console.ReadLine(), out frequency) || frequency <= 0)
            {
                Console.WriteLine("Введите положительное число");
            }Console.Write("Цена: ");
            decimal price;
            while (!decimal.TryParse(Console.ReadLine(), out price) || price <= 0)
            {
                Console.WriteLine("Введите положительное число");
            }

            Processor newProcessor = CreateProcessor(model, manufacturer, cores, frequency, price);
            AddProcessorToArray(newProcessor);

            Console.WriteLine("Процессор добавлен!");
            Console.ReadKey();
        }


## Projects & Experience

### Responsive Digital CV
*HTML | 2026*

* Designed and developed a professional resume using a two-column layout.

* Implemented **HTML5 semantic tags** (header, main, footer, aside) for better accessibility.

* Applied custom **CSS filtering** (grayscale effects) and responsive design principles.

## Education
### Belarusian-Russian University

*Bachelor of Software engineering | Expected June 2028*

Major: Software Engineering.

Current GPA: 8.0

## References
### Available upon request
Contact information of previous mentors and supervisors will be provided if needed.