# CA_maket
 CA_maket is a console program that demonstrates the main logic of the controller. C ++ implementation
 
 /*
 *  CA_maket.cpp
 *
 * Designed to practice the main logic of the controller
 * 
 * IDE - Microsoft Visual Studio 2019 v16.8.1
 *
 * All modules that use controller hardware resources
 * replaced by functions conditionally fulfilling the actions of the equipment
 * ZB: Instead of a real controller timer, the myTimer program module works
 *      with a conditional frequency of 100 Hz sets the support
 *      for logic timers from LT module
 * 
 * Logic timers can be created in the required number and assigned to
 *      working out the time intervals of the device logic functions
 * 
 * Also, modules are defined that contain the necessary triggers to enable
 *  and turning off some of the logical functions of the device,
 * Also - for restructuring the parameters of logical functions, etc. 
 *   
 * The functionality of the program will be increased in accordance with the development of flowcharts,
 *  running in parallel
 * 
 * For faster embedding of real code into the target controller, development is carried out in C ++
 * 
 * --- На русском -------------------------------------------------------------------------------------
 * 
 *  Предназначена для отработки основной логики контроллера
 *  Все модули, задействующие аппаратные ресурсы контроллера
 *  заменены на функции условно отрабатывающие действия аппаратуры
 *  ZB: Вместо реального таймера контроллера работает программный модуль myTimer
 *      с условной частотой 100Гц задает опору 
 *      для логических таймеров из модуля LT
 * 
 *      Логические таймеры могут быть созданы в нужном количестве и привязаны к
 *      отработке временных интервалов функций логики устройства
 * 
 *  Также определены модули, имеющие в составе необходимые триггеры для включения
 *  и выключения некоторых логических функций устройства,
 *  Также - для перестройки параметров логических функций и пр.
 * 
 *  Функционал программы будет наращиваться в согласии с разработкой блок-схем,
 *  ведущимся параллельно
 * 
 *  Для более быстрого встраивания настоящего кода в целевой контроллер разработка ведется на языке C++
 * 
 *  Created on: 25/12/2020
 *  Author: Starmark LN
 *  email:  ln.starmark@gmail.com
 *  email:  ln.starmark@ekatra.io
 *
*/



