# PDF Content Segmenter

## Setup Instructions
1. Install Java 8 or higher.
2. Clone the repository and navigate to the project directory.
3. Run `mvn install` to install the necessary dependencies (Apache PDFBox, JUnit).

## How to Run
Use the following command to run the application:

```bash
java -jar PdfSegmenter.jar <path-to-pdf> <number-of-cuts>
```

## Example Usage
```bash
java -jar PdfSegmenter.jar sample.pdf 3
```

## Unit Tests
Run the following command to execute the unit tests:

```bash
mvn test
```
