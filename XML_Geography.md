<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="_Z_gJE4rqEeqdU-y7qvz1lw" name="Geography" md:ref="platform:/plugin/com.indy.environment/technology/file/default.xml.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="_Z_gJFIrqEeqdU-y7qvz1lw" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xmlPath" id="_Z_gJFYrqEeqdU-y7qvz1lw" value="%{env:workspace_loc}%\Training\Files_In\Xml\geography.xml"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="_Z_gJForqEeqdU-y7qvz1lw" value="%{env:workspace_loc}%\Training\Files_In\Xml\geography.xsd"/>
  <attribute defType="com.stambia.xml.xsd.prefixForElement" id="_Z_gJF4rqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.prefixForAttribute" id="_Z_gJGIrqEeqdU-y7qvz1lw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.targetNamespace" id="_Z_gJGYrqEeqdU-y7qvz1lw" value="http://stambia.org/samples/geography"/>
  <node defType="com.stambia.xml.namespace" id="_Z_gJGorqEeqdU-y7qvz1lw" name="http://stambia.org/samples/geography">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_gJG4rqEeqdU-y7qvz1lw" value="geo"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="_Z_gJHIrqEeqdU-y7qvz1lw" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="_Z_gJHYrqEeqdU-y7qvz1lw" value="xs"/>
  </node>
  <node defType="com.stambia.xml.root" id="_Z_gJHorqEeqdU-y7qvz1lw" name="geography" position="0">
    <node defType="com.stambia.xml.sequence" id="_Z_gJH4rqEeqdU-y7qvz1lw" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gJIIrqEeqdU-y7qvz1lw" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gJIYrqEeqdU-y7qvz1lw" value="1"/>
      <node defType="com.stambia.xml.element" id="_Z_gJIorqEeqdU-y7qvz1lw" name="state" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gJI4rqEeqdU-y7qvz1lw" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gJJIrqEeqdU-y7qvz1lw" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="_Z_gJJYrqEeqdU-y7qvz1lw" value="geo:State"/>
        <node defType="com.stambia.xml.attribute" id="_Z_gJJorqEeqdU-y7qvz1lw" name="code" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gJJ4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gJKIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gJKYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gJKorqEeqdU-y7qvz1lw" name="upperCaseName" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gJK4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gJLIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gJLYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="_Z_gJLorqEeqdU-y7qvz1lw" name="stateName" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="_Z_gJL4rqEeqdU-y7qvz1lw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gJMIrqEeqdU-y7qvz1lw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="_Z_gJMYrqEeqdU-y7qvz1lw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="_Z_gJMorqEeqdU-y7qvz1lw" position="6">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="_Z_gJM4rqEeqdU-y7qvz1lw" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="_Z_gJNIrqEeqdU-y7qvz1lw" value="1"/>
          <node defType="com.stambia.xml.element" id="_Z_gJNYrqEeqdU-y7qvz1lw" name="city" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="_Z_gJNorqEeqdU-y7qvz1lw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="_Z_gJN4rqEeqdU-y7qvz1lw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="_Z_gJOIrqEeqdU-y7qvz1lw" value="geo:City"/>
            <node defType="com.stambia.xml.attribute" id="_Z_gJOYrqEeqdU-y7qvz1lw" name="cityName" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gJOorqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gJO4rqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gJPIrqEeqdU-y7qvz1lw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="_Z_gJPYrqEeqdU-y7qvz1lw" name="zipCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="_Z_gvAIrqEeqdU-y7qvz1lw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="_Z_gvAYrqEeqdU-y7qvz1lw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="_Z_gvAorqEeqdU-y7qvz1lw" value="optional"/>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>