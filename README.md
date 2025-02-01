Весь транспорт разделен на 2 главных пакета - civilian и military. 
civilian траспорт разделен на соответствующие пакеты - city,personal,railway,water. 
Классы Bus, Trolleybus имплементируются от класса PublicTransport.
От родительского класса PersonalTransport наследуются подклассы Bike, Car, Motorbike.
Класс Locomotive наследуется от родительского класса RailwayTransport 
и имплементирует интерфейс SteamTransport.
От родительского класса WaterTransport наследуются классы Boat,Steamship.Steamship 
иплементирует интерфейс SteamTransport.
От родительского класса MilitaryEquipment наследуются Fighter и Tank.