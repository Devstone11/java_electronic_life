# java_electronic_life


## Create the following classes

- `Herbivore` extends `AnimalEntity`
- `Carnivore` extends `AnimalEntity`
- `Plant` extends `PlantEntity`

**Tips:**

- I recommend you provide each with an image that is 96x96 pixels.
- See `ExampleAnimalEntity`, `ExamplePlantEntity` for examples.
- Read through all the parent Entity classes.
- Read through the `View` code to get an idea of how you can make your animals smarter.

## Add the new Entities to `Map`

- Replace the `ExampleAnimalEntity` and `ExamplePlantEntity` in `Map.java`


## Running

- In project root, create a `bin` directory.
- From the project root run the following commands to compile and execute:

```bash
javac -d bin/ -cp src src/com/galvanize/client/ElectronicLife.java
java -cp bin com.galvanize.client.ElectronicLife
```

## Bonus

- Add in whatever animals you want.
- Try to make a perfectly balanced ecosystem.
- Improve the map generation code.
- Try to make your animals more intelligent.