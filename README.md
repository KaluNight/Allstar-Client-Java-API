# Allstar API Java Client

Java client for the Allstar Partner API (auto-generated).

Use ``mvn clean compile`` to generate the code.

## Usage

```java
ApiClient apiClient = new ApiClient();

// To correctly define each key
((ApiKeyAuth) apiClient.getAuthentication("ApiKeyAuth")).setApiKey("valid-key");
((ApiKeyAuth) apiClient.getAuthentication("PublicApiKeyAuth")).setApiKey("valid-key");

LeagueApi leagueApi = new LeagueApi(apiClient);
``