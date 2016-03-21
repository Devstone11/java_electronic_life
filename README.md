# java_electronic_life

Let's put our Java skills to the test by recreating Eloquent Javascript's Project: Electronic Life in Java.

Instructions:

- Fork this repo.
- Make the specified changes.
- Push and pull request.

## Step One: Running The Application

- In project root, create a `bin` directory.
- From the project root run the following commands to compile and execute:

```bash
find . -name "*.java" > sources.txt
javac -d bin/ @sources.txt
java -cp bin com.galvanize.client.ElectronicLife
```

- **Tip:** seems like a good opportunity to create a bash script.

## Step Two: Research

- Figure out how the project is structured; where are Entities and other important classes are located?
- Research how things work.
  - Read through `ExampleAnimalEntity` and `ExamplePlantEntity`.
  - Read through the parent Entity classes.
  - Read through the `View` class.

## Step Three: Create the following classes

- `Herbivore` extends `AnimalEntity`
- `Carnivore` extends `AnimalEntity`
- `Plant` extends `PlantEntity`

**Tips:**

- I recommend you provide each with an image that is 96x96 pixels.
- The (PokeAPI)[http://pokeapi.co/] has some great images for this project.

## Step Four: Add your new Entities to `Map`

- Replace the `ExampleAnimalEntity` and `ExamplePlantEntity` in `Map.java` with your Entities.

## Bonus

- Add in whatever animals you want.
- Try to make a perfectly balanced ecosystem.
- Improve the map generation code.
- Try to make your animals more intelligent.
