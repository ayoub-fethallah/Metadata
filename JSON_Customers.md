<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.json.schema" id="_qFBVMC8yEey9PtmKoFlohA" md:ref="resource.tech#UUID_TECH_JSON1?fileId=UUID_TECH_JSON1$type=tech$name=json?" internalVersion="v1.0.0">
  <node defType="com.stambia.json.rootObject" id="_qh-W8C8yEey9PtmKoFlohA" name="customerList">
    <attribute defType="com.stambia.json.rootObject.encoding" id="_qjpK4C8yEey9PtmKoFlohA" value="UTF-8"/>
    <attribute defType="com.stambia.json.rootObject.reverseURLPath" id="_qkKvUC8yEey9PtmKoFlohA"/>
    <attribute defType="com.stambia.json.rootObject.reverseFilePath" id="_qkL9cC8yEey9PtmKoFlohA" value="C:\stb_sharepoint_resources_training\Dev\stambia_wks_DEV_Training\Training\Files_In\Json\sample_customer.json"/>
    <attribute defType="com.stambia.json.rootObject.filePath" id="_AT2u4C8zEey9PtmKoFlohA" value="%{env:workspace_loc}%\Training\Files_Out\Json\customerList.json"/>
    <node defType="com.stambia.json.array" id="_wSQ6ki8yEey9PtmKoFlohA" name="customer_list" position="1">
      <node defType="com.stambia.json.object" id="_wSQ6ky8yEey9PtmKoFlohA" name="item" position="1">
        <node defType="com.stambia.json.value" id="_wSQ6lC8yEey9PtmKoFlohA" name="firstName" position="1">
          <attribute defType="com.stambia.json.value.type" id="_wSQ6lS8yEey9PtmKoFlohA" value="string"/>
        </node>
        <node defType="com.stambia.json.value" id="_wSQ6li8yEey9PtmKoFlohA" name="lastName" position="2">
          <attribute defType="com.stambia.json.value.type" id="_wSQ6ly8yEey9PtmKoFlohA" value="string"/>
        </node>
        <node defType="com.stambia.json.value" id="_wSQ6mC8yEey9PtmKoFlohA" name="birthday" position="3">
          <attribute defType="com.stambia.json.value.type" id="_wSQ6mS8yEey9PtmKoFlohA" value="string"/>
        </node>
        <node defType="com.stambia.json.array" id="_wSQ6mi8yEey9PtmKoFlohA" name="address" position="4">
          <node defType="com.stambia.json.object" id="_wSQ6my8yEey9PtmKoFlohA" name="item" position="1">
            <node defType="com.stambia.json.value" id="_wSQ6nC8yEey9PtmKoFlohA" name="streetAddress" position="1">
              <attribute defType="com.stambia.json.value.type" id="_wSQ6nS8yEey9PtmKoFlohA" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_wSQ6ni8yEey9PtmKoFlohA" name="city" position="2">
              <attribute defType="com.stambia.json.value.type" id="_wSQ6ny8yEey9PtmKoFlohA" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_wSQ6oC8yEey9PtmKoFlohA" name="state" position="3">
              <attribute defType="com.stambia.json.value.type" id="_wSQ6oS8yEey9PtmKoFlohA" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_wSQ6oi8yEey9PtmKoFlohA" name="postalCode" position="4">
              <attribute defType="com.stambia.json.value.type" id="_wSQ6oy8yEey9PtmKoFlohA" value="string"/>
            </node>
          </node>
        </node>
        <node defType="com.stambia.json.array" id="_wSQ6pC8yEey9PtmKoFlohA" name="phoneNumber" position="5">
          <node defType="com.stambia.json.object" id="_wSQ6pS8yEey9PtmKoFlohA" name="item" position="1">
            <node defType="com.stambia.json.value" id="_wSQ6pi8yEey9PtmKoFlohA" name="type" position="1">
              <attribute defType="com.stambia.json.value.type" id="_wSQ6py8yEey9PtmKoFlohA" value="string"/>
            </node>
            <node defType="com.stambia.json.value" id="_wSQ6qC8yEey9PtmKoFlohA" name="number" position="2">
              <attribute defType="com.stambia.json.value.type" id="_wSQ6qS8yEey9PtmKoFlohA" value="string"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>