### Hi everyone! 👋
Im MikeTheHash im a skilled programmer for 2 years,

    using System;

    class MikeTheHash{
        string[] programming_lang_knowledge = {"C#", "C", "Java"};
        string[] scripting_lang_knowledge = {"Python", "Javascript", "Php"};
        string[] markup_lang_knowledge = {"HTML", "CSS"};
        string[] os_lang_knowledge = {"Bash", "Batch"};
        public string say_hello(){
           string HelloVar = "Hello Everyone!";
           return HelloVar;
        }
    }
    
    class Program{
        static void Main(){
           MikeTheHash Mike = new MikeTheHash();
           Mike.say_hello();
        }
    }
