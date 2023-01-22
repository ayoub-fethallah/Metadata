<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.xml.xsd" id="__vv6UpXkEeqi4I9zkaUtjw" name="hotelManagement.xsd" md:ref="platform:/plugin/com.indy.environment/technology/file/default.xml.md#UUID_MD_XML_DEFAULT?fileId=UUID_MD_XML_DEFAULT$type=md$name=Xml?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.xml.xsd.xsdReverseVersion" id="__vv6U5XkEeqi4I9zkaUtjw" value="1"/>
  <attribute defType="com.stambia.xml.xsd.xsdPath" id="__vwhQJXkEeqi4I9zkaUtjw" value="%{env:workspace_loc}%\Training\Files_In\Xml\hotelManagement.xsd"/>
  <attribute defType="com.stambia.xml.xsd.prefixForElement" id="__vwhQZXkEeqi4I9zkaUtjw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.prefixForAttribute" id="__vwhQpXkEeqi4I9zkaUtjw" value="unqualified"/>
  <attribute defType="com.stambia.xml.xsd.targetNamespace" id="__vwhQ5XkEeqi4I9zkaUtjw" value="http://stambia.org/samples/management"/>
  <node defType="com.stambia.xml.namespace" id="__vwhRZXkEeqi4I9zkaUtjw" name="http://stambia.org/samples/common">
    <attribute defType="com.stambia.xml.namespace.prefix" id="__vwhRpXkEeqi4I9zkaUtjw" value="com"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="__vwhR5XkEeqi4I9zkaUtjw" name="http://stambia.org/samples/management">
    <attribute defType="com.stambia.xml.namespace.prefix" id="__vwhSJXkEeqi4I9zkaUtjw" value="mgt"/>
  </node>
  <node defType="com.stambia.xml.namespace" id="__vwhSZXkEeqi4I9zkaUtjw" name="http://www.w3.org/2001/XMLSchema">
    <attribute defType="com.stambia.xml.namespace.prefix" id="__vwhSpXkEeqi4I9zkaUtjw" value="xs"/>
  </node>
  <node defType="com.stambia.xml.root" id="__vwhS5XkEeqi4I9zkaUtjw" name="hotelManagement" position="0">
    <node defType="com.stambia.xml.sequence" id="__vwhTJXkEeqi4I9zkaUtjw" position="3">
      <attribute defType="com.stambia.xml.sequence.minOccurs" id="__vwhTZXkEeqi4I9zkaUtjw" value="1"/>
      <attribute defType="com.stambia.xml.sequence.maxOccurs" id="__vwhTpXkEeqi4I9zkaUtjw" value="1"/>
      <node defType="com.stambia.xml.element" id="__vwhT5XkEeqi4I9zkaUtjw" name="customer" position="0">
        <attribute defType="com.stambia.xml.element.minOccurs" id="__vwhUJXkEeqi4I9zkaUtjw" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwhUZXkEeqi4I9zkaUtjw" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="__vwhUpXkEeqi4I9zkaUtjw" value="mgt:CustomerDetail"/>
        <node defType="com.stambia.xml.attribute" id="__vwhU5XkEeqi4I9zkaUtjw" name="customerId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwhVJXkEeqi4I9zkaUtjw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhVZXkEeqi4I9zkaUtjw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwhVpXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwhV5XkEeqi4I9zkaUtjw" name="titleCode" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwhWJXkEeqi4I9zkaUtjw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhWZXkEeqi4I9zkaUtjw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwhWpXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwhW5XkEeqi4I9zkaUtjw" name="title" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwhXJXkEeqi4I9zkaUtjw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhXZXkEeqi4I9zkaUtjw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwhXpXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwhX5XkEeqi4I9zkaUtjw" name="firstName" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwhYJXkEeqi4I9zkaUtjw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhYZXkEeqi4I9zkaUtjw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwhYpXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwhY5XkEeqi4I9zkaUtjw" name="lastName" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwhZJXkEeqi4I9zkaUtjw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhZZXkEeqi4I9zkaUtjw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwhZpXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwhZ5XkEeqi4I9zkaUtjw" name="company" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwhaJXkEeqi4I9zkaUtjw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhaZXkEeqi4I9zkaUtjw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwhapXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwha5XkEeqi4I9zkaUtjw" name="birthDate" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwhbJXkEeqi4I9zkaUtjw" value="dateTime"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhbZXkEeqi4I9zkaUtjw" value="xs:dateTime"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwhbpXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="__vwhb5XkEeqi4I9zkaUtjw" position="10">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="__vwhcJXkEeqi4I9zkaUtjw" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="__vwhcZXkEeqi4I9zkaUtjw" value="1"/>
          <node defType="com.stambia.xml.element" id="__vwhcpXkEeqi4I9zkaUtjw" name="address" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="__vwhc5XkEeqi4I9zkaUtjw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwhdJXkEeqi4I9zkaUtjw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="__vwhdZXkEeqi4I9zkaUtjw" value="com:Address"/>
            <node defType="com.stambia.xml.attribute" id="__vwhdpXkEeqi4I9zkaUtjw" name="addressId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhd5XkEeqi4I9zkaUtjw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwheJXkEeqi4I9zkaUtjw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwheZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhepXkEeqi4I9zkaUtjw" name="line1" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhe5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhfJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhfZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhfpXkEeqi4I9zkaUtjw" name="line2" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhf5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhgJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhgZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhgpXkEeqi4I9zkaUtjw" name="line3" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhg5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhhJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhhZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhhpXkEeqi4I9zkaUtjw" name="line4" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhh5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhiJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhiZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhipXkEeqi4I9zkaUtjw" name="zipCode" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhi5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhjJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhjZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhjpXkEeqi4I9zkaUtjw" name="city" position="6">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhj5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhkJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhkZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhkpXkEeqi4I9zkaUtjw" name="stateCode" position="7">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhk5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhlJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhlZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="__vwhlpXkEeqi4I9zkaUtjw" name="phone" position="1">
            <attribute defType="com.stambia.xml.element.minOccurs" id="__vwhl5XkEeqi4I9zkaUtjw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwhmJXkEeqi4I9zkaUtjw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="__vwhmZXkEeqi4I9zkaUtjw" value="com:Phone"/>
            <node defType="com.stambia.xml.attribute" id="__vwhmpXkEeqi4I9zkaUtjw" name="phoneId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhm5XkEeqi4I9zkaUtjw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhnJXkEeqi4I9zkaUtjw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhnZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhnpXkEeqi4I9zkaUtjw" name="phoneTypeCode" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhn5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhoJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhoZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhopXkEeqi4I9zkaUtjw" name="phoneNumber" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwho5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhpJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhpZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhppXkEeqi4I9zkaUtjw" name="phoneType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhp5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhqJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhqZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhqpXkEeqi4I9zkaUtjw" name="phoningAllowed" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhq5XkEeqi4I9zkaUtjw" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhrJXkEeqi4I9zkaUtjw" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhrZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="__vwhrpXkEeqi4I9zkaUtjw" name="email" position="2">
            <attribute defType="com.stambia.xml.element.minOccurs" id="__vwhr5XkEeqi4I9zkaUtjw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwhsJXkEeqi4I9zkaUtjw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="__vwhsZXkEeqi4I9zkaUtjw" value="com:Email"/>
            <node defType="com.stambia.xml.attribute" id="__vwhspXkEeqi4I9zkaUtjw" name="emailId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhs5XkEeqi4I9zkaUtjw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhtJXkEeqi4I9zkaUtjw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhtZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhtpXkEeqi4I9zkaUtjw" name="emailAddress" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwht5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhuJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhuZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhupXkEeqi4I9zkaUtjw" name="emailType" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhu5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhvJXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhvZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhvpXkEeqi4I9zkaUtjw" name="mailingAllowed" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhv5XkEeqi4I9zkaUtjw" value="boolean"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhwJXkEeqi4I9zkaUtjw" value="xs:boolean"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhwZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
          </node>
          <node defType="com.stambia.xml.element" id="__vwhwpXkEeqi4I9zkaUtjw" name="bill" position="3">
            <attribute defType="com.stambia.xml.element.minOccurs" id="__vwhw5XkEeqi4I9zkaUtjw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwhxJXkEeqi4I9zkaUtjw" value="-1"/>
            <attribute defType="com.stambia.xml.element.originalType" id="__vwhxZXkEeqi4I9zkaUtjw" value="com:Bill"/>
            <node defType="com.stambia.xml.attribute" id="__vwhxpXkEeqi4I9zkaUtjw" name="billId" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhx5XkEeqi4I9zkaUtjw" value="integer"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhyJXkEeqi4I9zkaUtjw" value="xs:integer"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhyZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhypXkEeqi4I9zkaUtjw" name="billDate" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhy5XkEeqi4I9zkaUtjw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwhzJXkEeqi4I9zkaUtjw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwhzZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwhzpXkEeqi4I9zkaUtjw" name="paymentTypeCode" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwhz5XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh0JXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwh0ZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwh0pXkEeqi4I9zkaUtjw" name="paymentType" position="3">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwh05XkEeqi4I9zkaUtjw" value="string"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh1JXkEeqi4I9zkaUtjw" value="xs:string"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwh1ZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwh1pXkEeqi4I9zkaUtjw" name="paymentDate" position="4">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwh15XkEeqi4I9zkaUtjw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh2JXkEeqi4I9zkaUtjw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwh2ZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwh2pXkEeqi4I9zkaUtjw" name="totalAmount" position="5">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwh25XkEeqi4I9zkaUtjw" value="decimal"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh3JXkEeqi4I9zkaUtjw" value="xs:decimal"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwh3ZXkEeqi4I9zkaUtjw" value="optional"/>
            </node>
          </node>
        </node>
        <node defType="com.stambia.xml.propertyField" id="__vwh3pXkEeqi4I9zkaUtjw" name="sortLastname">
          <attribute defType="com.stambia.xml.propertyField.property" id="__vwh35XkEeqi4I9zkaUtjw" value="sortKey"/>
        </node>
        <node defType="com.stambia.xml.propertyField" id="__vwh4JXkEeqi4I9zkaUtjw" name="SortFirstname">
          <attribute defType="com.stambia.xml.propertyField.property" id="__vwh4ZXkEeqi4I9zkaUtjw" value="sortKey"/>
        </node>
      </node>
      <node defType="com.stambia.xml.element" id="__vwh4pXkEeqi4I9zkaUtjw" name="bedroom" position="1">
        <attribute defType="com.stambia.xml.element.minOccurs" id="__vwh45XkEeqi4I9zkaUtjw" value="0"/>
        <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwh5JXkEeqi4I9zkaUtjw" value="-1"/>
        <attribute defType="com.stambia.xml.element.originalType" id="__vwh5ZXkEeqi4I9zkaUtjw" value="mgt:Bedroom"/>
        <node defType="com.stambia.xml.attribute" id="__vwh5pXkEeqi4I9zkaUtjw" name="bedroomId" position="0">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwh55XkEeqi4I9zkaUtjw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh6JXkEeqi4I9zkaUtjw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwh6ZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwh6pXkEeqi4I9zkaUtjw" name="roomNumber" position="1">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwh65XkEeqi4I9zkaUtjw" value="integer"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh7JXkEeqi4I9zkaUtjw" value="xs:integer"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwh7ZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwh7pXkEeqi4I9zkaUtjw" name="floor" position="2">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwh75XkEeqi4I9zkaUtjw" value="short"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh8JXkEeqi4I9zkaUtjw" value="xs:short"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwh8ZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwh8pXkEeqi4I9zkaUtjw" name="bath" position="3">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwh85XkEeqi4I9zkaUtjw" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh9JXkEeqi4I9zkaUtjw" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwh9ZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwh9pXkEeqi4I9zkaUtjw" name="shower" position="4">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwh95XkEeqi4I9zkaUtjw" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh-JXkEeqi4I9zkaUtjw" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwh-ZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwh-pXkEeqi4I9zkaUtjw" name="bar" position="5">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwh-5XkEeqi4I9zkaUtjw" value="boolean"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwh_JXkEeqi4I9zkaUtjw" value="xs:boolean"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwh_ZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwh_pXkEeqi4I9zkaUtjw" name="bedCount" position="6">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwh_5XkEeqi4I9zkaUtjw" value="short"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiAJXkEeqi4I9zkaUtjw" value="xs:short"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwiAZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwiApXkEeqi4I9zkaUtjw" name="phoneNumber" position="7">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwiA5XkEeqi4I9zkaUtjw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiBJXkEeqi4I9zkaUtjw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwiBZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.attribute" id="__vwiBpXkEeqi4I9zkaUtjw" name="bedroomType" position="8">
          <attribute defType="com.stambia.xml.attribute.type" id="__vwiB5XkEeqi4I9zkaUtjw" value="string"/>
          <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiCJXkEeqi4I9zkaUtjw" value="xs:string"/>
          <attribute defType="com.stambia.xml.attribute.use" id="__vwiCZXkEeqi4I9zkaUtjw" value="optional"/>
        </node>
        <node defType="com.stambia.xml.sequence" id="__vwiCpXkEeqi4I9zkaUtjw" position="12">
          <attribute defType="com.stambia.xml.sequence.minOccurs" id="__vwiC5XkEeqi4I9zkaUtjw" value="1"/>
          <attribute defType="com.stambia.xml.sequence.maxOccurs" id="__vwiDJXkEeqi4I9zkaUtjw" value="1"/>
          <node defType="com.stambia.xml.element" id="__vwiDZXkEeqi4I9zkaUtjw" name="priceRange" position="0">
            <attribute defType="com.stambia.xml.element.minOccurs" id="__vwiDpXkEeqi4I9zkaUtjw" value="0"/>
            <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwiD5XkEeqi4I9zkaUtjw" value="-1"/>
            <node defType="com.stambia.xml.attribute" id="__vwiEJXkEeqi4I9zkaUtjw" name="startDate" position="0">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwiEZXkEeqi4I9zkaUtjw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiEpXkEeqi4I9zkaUtjw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwiE5XkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwiFJXkEeqi4I9zkaUtjw" name="endDate" position="1">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwiFZXkEeqi4I9zkaUtjw" value="dateTime"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiFpXkEeqi4I9zkaUtjw" value="xs:dateTime"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwiF5XkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.attribute" id="__vwiGJXkEeqi4I9zkaUtjw" name="price" position="2">
              <attribute defType="com.stambia.xml.attribute.type" id="__vwiGZXkEeqi4I9zkaUtjw" value="decimal"/>
              <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiGpXkEeqi4I9zkaUtjw" value="xs:decimal"/>
              <attribute defType="com.stambia.xml.attribute.use" id="__vwiG5XkEeqi4I9zkaUtjw" value="optional"/>
            </node>
            <node defType="com.stambia.xml.sequence" id="__vwiHJXkEeqi4I9zkaUtjw" position="6">
              <attribute defType="com.stambia.xml.sequence.minOccurs" id="__vwiHZXkEeqi4I9zkaUtjw" value="1"/>
              <attribute defType="com.stambia.xml.sequence.maxOccurs" id="__vwiHpXkEeqi4I9zkaUtjw" value="1"/>
              <node defType="com.stambia.xml.element" id="__vwiH5XkEeqi4I9zkaUtjw" name="occupation" position="0">
                <attribute defType="com.stambia.xml.element.minOccurs" id="__vwiIJXkEeqi4I9zkaUtjw" value="0"/>
                <attribute defType="com.stambia.xml.element.maxOccurs" id="__vwiIZXkEeqi4I9zkaUtjw" value="-1"/>
                <attribute defType="com.stambia.xml.element.originalType" id="__vwiIpXkEeqi4I9zkaUtjw" value="com:Occupation"/>
                <node defType="com.stambia.xml.attribute" id="__vwiI5XkEeqi4I9zkaUtjw" name="customerId" position="0">
                  <attribute defType="com.stambia.xml.attribute.type" id="__vwiJJXkEeqi4I9zkaUtjw" value="integer"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiJZXkEeqi4I9zkaUtjw" value="xs:integer"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="__vwiJpXkEeqi4I9zkaUtjw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="__vwiJ5XkEeqi4I9zkaUtjw" name="occupationDate" position="1">
                  <attribute defType="com.stambia.xml.attribute.type" id="__vwiKJXkEeqi4I9zkaUtjw" value="dateTime"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiKZXkEeqi4I9zkaUtjw" value="xs:dateTime"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="__vwiKpXkEeqi4I9zkaUtjw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="__vwiK5XkEeqi4I9zkaUtjw" name="personCount" position="2">
                  <attribute defType="com.stambia.xml.attribute.type" id="__vwiLJXkEeqi4I9zkaUtjw" value="short"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiLZXkEeqi4I9zkaUtjw" value="xs:short"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="__vwiLpXkEeqi4I9zkaUtjw" value="optional"/>
                </node>
                <node defType="com.stambia.xml.attribute" id="__vwiL5XkEeqi4I9zkaUtjw" name="booked" position="3">
                  <attribute defType="com.stambia.xml.attribute.type" id="__vwiMJXkEeqi4I9zkaUtjw" value="boolean"/>
                  <attribute defType="com.stambia.xml.attribute.originalType" id="__vwiMZXkEeqi4I9zkaUtjw" value="xs:boolean"/>
                  <attribute defType="com.stambia.xml.attribute.use" id="__vwiMpXkEeqi4I9zkaUtjw" value="optional"/>
                </node>
              </node>
            </node>
          </node>
        </node>
      </node>
    </node>
  </node>
</md:node>