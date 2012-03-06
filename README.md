### Basic Steps:
1. Clone this repository
3. Run: `./gradlew init`
4. Gripes will create a `conf/gripes-basic.gradle` file, edit the gripes{} section if needed
5. Run: `./gradlew setup`

### To Create Models and ActionBeans:
5. First entity class: `./gradlew create -Pmodel=Page`
6. Edit the entity, adding properties (i.e. String name, description)
7. Create actions: `./gradlew create -Paction=Page`
8. Run the app: `./gradlew run`
9. Browse: http://localhost:8888/gripes

### Running
10. `./gradlew run`