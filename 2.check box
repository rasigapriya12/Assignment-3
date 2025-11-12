import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.ChoiceBox;
import javafx.scene.control.Label;
import javafx.scene.layout.VBox;
import javafx.stage.Stage;

public class ColorChoiceBox extends Application {
    @Override
    public void start(Stage stage) {
        Label label = new Label("Select a color:");
        ChoiceBox<String> choiceBox = new ChoiceBox<>();
        choiceBox.getItems().addAll("Red", "Green", "Blue", "Yellow", "Pink");

        Label result = new Label("No color selected");

       
        choiceBox.getSelectionModel().selectedItemProperty().addListener((obs, oldVal, newVal) -> {
            result.setText("You selected: " + newVal);
        });

        VBox root = new VBox(10, label, choiceBox, result);
        Scene scene = new Scene(root, 300, 150);

        stage.setTitle("ChoiceBox Example");
        stage.setScene(scene);
        stage.show();
    }

    public static void main(String[] args) {
        launch(args);
    }
}
