# Vaadin_Repo
Това е примерен проект направен с фреймуорка Vaadin

Инсталиране:

Начин 1:
- Директно клониране на репо-то в Eclipse
- В Eclipse се отива на File -> Import, а там от менюто се избира Git -> Projects From Git -> Clone URI
- Въвежда се линка на клониране на това репо

Начин 2:
- Сваля се репото като Zip
- В Eclipse се отива на File -> Import, а там от менюто се избира Maven -> Existing Maven Project
- Избира се дирекаторията на вече сваления архив, след което се избира проекта и се импортира в текущия уоркспейс

Запускане:
- След като проектът е вече импортиран се натиска Десен Бутон върху него Run As -> Maven Install
- Автоматично се свалят необходимите библиотеки, след което се инсталират на машината
- След като инсталацията е минала, се натиска отново Десен Бутон върху проекта и се отива на Run As -> Maven Build
- В отворилия се прозорец, в полето "goals" се изписва jetty:run, след което се натиска Run.
- След като приложението е готово за запускане, отиваме горе в лентат с инструменти, отиваме на бутона Run As и избираме нашия проект.

Достъпване:
- Проектът е конфигуриран да работи на порт 8080 така че се убедете, че нищо не работи на този порт
- В браузър по избор се отива на http://localhost:8080
