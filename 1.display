import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.Label;
import javafx.scene.layout.VBox;
import javafx.stage.Stage;

public class HelloJavaFX extends Application {
    @Override
    public void start(Stage stage) {
        Label msg = new Label("Hello, JavaFX!");
        String javaVersion = System.getProperty("java.version");
        String javafxVersion = System.getProperty("javafx.version");

        Label versions = new Label("Java Version: " + javaVersion + "\nJavaFX Version: " + javafxVersion);

        VBox root = new VBox(10, msg, versions);
        Scene scene = new Scene(root, 300, 150);

        stage.setTitle("JavaFX Example");
        stage.setScene(scene);
        stage.show();
    }

    public static void main(String[] args) {
        launch(args);
    }
}
