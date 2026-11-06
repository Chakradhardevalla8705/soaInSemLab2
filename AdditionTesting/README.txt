ADDITION TESTING - ECLIPSE PROJECT

IMPORT:
1. Extract AdditionTesting.zip.
2. In Eclipse choose File > Import.
3. Choose Maven > Existing Maven Projects > Next.
4. Browse to the extracted AdditionTesting folder.
5. Select the pom.xml project and click Finish.
6. Wait for Maven dependencies to download.

RUN TEST:
1. Open src/test/java > com.example.demo > AddControllerTest.java.
2. Right-click the file > Run As > JUnit Test.
3. Expected: 1 test, 0 failures (green bar).

RUN APPLICATION:
1. Right-click AdditionTestingApplication.java.
2. Run As > Java Application (or Spring Boot App if available).
3. Open http://localhost:8080/ms1/add?a=-5&b=5
4. Expected response: MS 1.1 - Addition = 0

Requires JDK 17 or later and internet access for Maven dependency download.
