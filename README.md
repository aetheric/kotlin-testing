# Kotlin: Testing
A simple aggregator pom with kotlin test dependencies.

## Usage

```xml
<project>

	...

	<dependencyManagement>
		<dependencies>

			...

			<dependency>
				<scope>import</scope>
				<groupId>nz.co.aetheric</groupId>
				<artifactId>kotlin-testing</artifactId>
				<version>...</version>
			</dependency>

			...

		</dependencies>
	</dependencyManagement>

	...

</project>
```
