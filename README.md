# wiremock-docker

```
curl --location --request POST 'localhost:8080/soap' \
--header 'Content-Type: application/xml' \
--data-raw '<soap:Envelope xmlns:soap="http://www.w3.org/2003/05/soap-envelope/">
    <soap:Body>
        <m:a>
            <m:test>success</m:test>
        </m:a>
    </soap:Body>
</soap:Envelope>'
```