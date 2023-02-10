# Takenoko

## Prerequisites
- Maven
- Java 17

## Building
>>      mvn clean package

## Running
>A single game between BotMVP, BotParcelle, BotMoyen and BotRandom with the board shown
>>      mvn exec:java -Dexec.args="--demo"

>Simulating 1000 games between BotMVP and BotMoyen then 1000 games between 4 BotMVPs
>>      mvn exec:java -Dexec.args="--2thousands"

>Simulating 1000 games between BotJardinier, BotParcelle and BotPanda
>>      mvn exec:java -Dexec.args="--botsfocus"

>Simulating 1000 games between BotMVP and BotMoyen whose result's stats is saved in /stats
>>      mvn exec:java -Dexec.args="--csv"



