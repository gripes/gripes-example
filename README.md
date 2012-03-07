### Basic Steps:
1. Clone this repository
3. Run: `./gradlew init`
4. Gripes will create a `conf/gripes-basic.gradle` file, edit the gripes{} section if needed
5. Run: `./gradlew setup`

### To Create Models and ActionBeans (Optional):
1. First entity class: `./gradlew create -Pmodel=Page`
2. Edit the entity, adding properties (i.e. String name, description)
3. Create actions: `./gradlew create -Paction=Page`

### Create pages
1. Create pages (html,jsp,etc..) under /web
	- /web/test.html -> http://localhost:8888/gripes/test.html (default server settings)

### Running
1. `./gradlew run`
2. Browse: http://localhost:8888/gripes