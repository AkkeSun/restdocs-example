# [SPRING REST Docs Example]

수정일 : 2024.03.08

1. API 문서 작성을 위한 테스트코드를 작성합니다
2. 테스트코드가 성공하면 build > generated-snippets 에 adoc 파일이 생성됩니다
3. src > docs > asciidoc > index.adoc 을 수정합니다
4. ./gradlew asciidoctor 를 호출하면 build > docs 에 API 문서가 생성된다
5. ./gradlew copyDocument 를 호출하면 API 문서가 src > main > resources > template 으로 복사됩니다