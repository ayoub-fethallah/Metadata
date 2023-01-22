<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.http.rest" id="_ix7asC81Eey9PtmKoFlohA" md:ref="resource.tech#UUID_TECH_HTTPREST?fileId=UUID_TECH_HTTPREST$type=tech$name=HttpRest?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.http.rest.module" id="_iywhIC81Eey9PtmKoFlohA" value="HttpRest"/>
  <attribute defType="com.stambia.http.rest.security" id="_7M9mMC81Eey9PtmKoFlohA"/>
  <attribute defType="com.stambia.http.rest.proxy" id="_7M-0UC81Eey9PtmKoFlohA"/>
  <attribute defType="com.stambia.http.rest.reverseUrl" id="_7M_bYC81Eey9PtmKoFlohA" value="http://DESKTOP-5JAPCE7:42200/rest/StambiaDeliveryService/3/default?openapi3.json"/>
  <attribute defType="com.stambia.http.rest.url" id="_7M_bYS81Eey9PtmKoFlohA" value="http://DESKTOP-5JAPCE7:42200/rest/StambiaDeliveryService/3/default"/>
  <node defType="com.stambia.http.rest.path" id="_7M7J_i81Eey9PtmKoFlohA" name="/getJSCustomerDetails">
    <attribute defType="com.stambia.http.rest.path.path" id="_7M7J_y81Eey9PtmKoFlohA" value="/getJSCustomerDetails"/>
    <node defType="com.stambia.http.rest.operation" id="_7M7KAC81Eey9PtmKoFlohA" name="GET">
      <attribute defType="com.stambia.http.rest.operation.method" id="_7M7KAS81Eey9PtmKoFlohA" value="GET"/>
      <attribute defType="com.stambia.http.rest.operation.operationId" id="_7M7KAi81Eey9PtmKoFlohA" value="getJSCustomerDetails"/>
      <node defType="com.stambia.http.rest.parameters" id="_7M7KAy81Eey9PtmKoFlohA">
        <node defType="com.stambia.http.rest.parameter" id="_7M7KBC81Eey9PtmKoFlohA" name="cust_id">
          <attribute defType="com.stambia.http.rest.parameter.method" id="_7M7KBS81Eey9PtmKoFlohA" value="cust_id"/>
          <attribute defType="com.stambia.http.rest.parameter.location" id="_7M7KBi81Eey9PtmKoFlohA" value="query"/>
          <attribute defType="com.stambia.http.rest.parameter.required" id="_7M7KBy81Eey9PtmKoFlohA" value="false"/>
        </node>
      </node>
      <node defType="com.stambia.http.rest.responses" id="_7M7KCC81Eey9PtmKoFlohA">
        <node defType="com.stambia.http.rest.response" id="_7M7KCS81Eey9PtmKoFlohA" name="200">
          <attribute defType="com.stambia.http.rest.response.code" id="_7M7KCi81Eey9PtmKoFlohA" value="200"/>
          <attribute defType="com.stambia.http.rest.response.description" id="_7M7KCy81Eey9PtmKoFlohA" value="200 response"/>
          <node defType="com.stambia.http.rest.content" id="_7M7KDC81Eey9PtmKoFlohA" name="application/json">
            <attribute defType="com.stambia.http.rest.content.mediaType" id="_7M7KDS81Eey9PtmKoFlohA" value="JSON"/>
            <attribute defType="com.stambia.http.rest.content.contentType" id="_7M7KDi81Eey9PtmKoFlohA" value="application/json"/>
            <node defType="com.stambia.json.rootObject" id="_7M7KDy81Eey9PtmKoFlohA" name="customerList">
              <node defType="com.stambia.json.array" id="_7M7KEC81Eey9PtmKoFlohA" name="customer_list">
                <node defType="com.stambia.json.object" id="_7M7KES81Eey9PtmKoFlohA">
                  <node defType="com.stambia.json.value" id="_7M7KEi81Eey9PtmKoFlohA" name="firstName">
                    <attribute defType="com.stambia.json.value.type" id="_7M7KEy81Eey9PtmKoFlohA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_7M7KFC81Eey9PtmKoFlohA" name="lastName">
                    <attribute defType="com.stambia.json.value.type" id="_7M7KFS81Eey9PtmKoFlohA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.value" id="_7M7KFi81Eey9PtmKoFlohA" name="birthday">
                    <attribute defType="com.stambia.json.value.type" id="_7M7KFy81Eey9PtmKoFlohA" value="string"/>
                  </node>
                  <node defType="com.stambia.json.array" id="_7M7KGC81Eey9PtmKoFlohA" name="address">
                    <node defType="com.stambia.json.object" id="_7M7KGS81Eey9PtmKoFlohA">
                      <node defType="com.stambia.json.value" id="_7M7KGi81Eey9PtmKoFlohA" name="streetAddress">
                        <attribute defType="com.stambia.json.value.type" id="_7M7KGy81Eey9PtmKoFlohA" value="string"/>
                      </node>
                      <node defType="com.stambia.json.value" id="_7M7KHC81Eey9PtmKoFlohA" name="city">
                        <attribute defType="com.stambia.json.value.type" id="_7M7KHS81Eey9PtmKoFlohA" value="string"/>
                      </node>
                      <node defType="com.stambia.json.value" id="_7M7KHi81Eey9PtmKoFlohA" name="state">
                        <attribute defType="com.stambia.json.value.type" id="_7M7KHy81Eey9PtmKoFlohA" value="string"/>
                      </node>
                      <node defType="com.stambia.json.value" id="_7M7KIC81Eey9PtmKoFlohA" name="postalCode">
                        <attribute defType="com.stambia.json.value.type" id="_7M7KIS81Eey9PtmKoFlohA" value="string"/>
                      </node>
                    </node>
                  </node>
                  <node defType="com.stambia.json.array" id="_7M7KIi81Eey9PtmKoFlohA" name="phoneNumber">
                    <node defType="com.stambia.json.object" id="_7M7KIy81Eey9PtmKoFlohA">
                      <node defType="com.stambia.json.value" id="_7M7KJC81Eey9PtmKoFlohA" name="type">
                        <attribute defType="com.stambia.json.value.type" id="_7M7KJS81Eey9PtmKoFlohA" value="string"/>
                      </node>
                      <node defType="com.stambia.json.value" id="_7M7xAC81Eey9PtmKoFlohA" name="number">
                        <attribute defType="com.stambia.json.value.type" id="_7M7xAS81Eey9PtmKoFlohA" value="string"/>
                      </node>
                    </node>
                  </node>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>