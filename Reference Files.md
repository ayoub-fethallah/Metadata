<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.file.server" id="_5PO9sDxREe2hvaPj18Ug5Q" md:ref="resource.md#UUID_TECH_FILE_MD?fileId=UUID_TECH_FILE_MD$type=md$name=File?" internalVersion="v1.0.0">
  <node defType="com.stambia.file.directory" id="_5Ym8IDxREe2hvaPj18Ug5Q" name="Reference Files Folder">
    <attribute defType="com.stambia.file.directory.path" id="_5ZCZ8DxREe2hvaPj18Ug5Q" value="C:\stambia_wks_DEV_Training\Training\Files_In\Reference_Files"/>
    <node defType="com.stambia.file.file" id="_5ZGEUDxREe2hvaPj18Ug5Q" name="DiscountRanges">
      <attribute defType="com.stambia.file.file.type" id="_5aZr4DxREe2hvaPj18Ug5Q" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_5afygDxREe2hvaPj18Ug5Q" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_5agZkDxREe2hvaPj18Ug5Q" value="2C"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_5ahnsDxREe2hvaPj18Ug5Q" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_5ajc4DxREe2hvaPj18Ug5Q" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_5akD8DxREe2hvaPj18Ug5Q" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_5akrADxREe2hvaPj18Ug5Q" value="1"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_uguXIDxSEe2hvaPj18Ug5Q" value="DiscountRanges.txt"/>
      <node defType="com.stambia.file.field" id="_w4WV0DxSEe2hvaPj18Ug5Q" name="min" position="1">
        <attribute defType="com.stambia.file.field.size" id="_w4WV0TxSEe2hvaPj18Ug5Q" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_w4WV0jxSEe2hvaPj18Ug5Q" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_w4WV0zxSEe2hvaPj18Ug5Q" value="MIN"/>
      </node>
      <node defType="com.stambia.file.field" id="_w4WV1DxSEe2hvaPj18Ug5Q" name="max" position="2">
        <attribute defType="com.stambia.file.field.size" id="_w4WV1TxSEe2hvaPj18Ug5Q" value="12"/>
        <attribute defType="com.stambia.file.field.type" id="_w4WV1jxSEe2hvaPj18Ug5Q" value="Numeric"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_w4WV1zxSEe2hvaPj18Ug5Q" value="MAX"/>
      </node>
      <node defType="com.stambia.file.field" id="_w4WV2DxSEe2hvaPj18Ug5Q" name="range" position="3">
        <attribute defType="com.stambia.file.field.size" id="_w4WV2TxSEe2hvaPj18Ug5Q" value="62"/>
        <attribute defType="com.stambia.file.field.type" id="_w4WV2jxSEe2hvaPj18Ug5Q" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_w4WV2zxSEe2hvaPj18Ug5Q" value="RANGE"/>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_f5e_cEAMEe2U8vhnCytY6A" name="ref_us_cities">
      <attribute defType="com.stambia.file.file.type" id="_f7CeoEAMEe2U8vhnCytY6A" value="POSITIONAL"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_f7HXIEAMEe2U8vhnCytY6A" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_f7H-MEAMEe2U8vhnCytY6A" value="3B"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_f7JMUEAMEe2U8vhnCytY6A" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_f7KacEAMEe2U8vhnCytY6A" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_f7LokEAMEe2U8vhnCytY6A" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_f7MPoEAMEe2U8vhnCytY6A" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_hCl8kEAMEe2U8vhnCytY6A" value="ref_us_cities.txt"/>
      <node defType="com.stambia.file.field" id="_jfsRIEAMEe2U8vhnCytY6A" name="ZIP_CODE" position="1">
        <attribute defType="com.stambia.file.field.size" id="_jftfQEAMEe2U8vhnCytY6A" value="5"/>
        <attribute defType="com.stambia.file.field.type" id="_jftfQUAMEe2U8vhnCytY6A" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_jftfQkAMEe2U8vhnCytY6A" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_jfzl4EAMEe2U8vhnCytY6A" name="CITY" position="6">
        <attribute defType="com.stambia.file.field.size" id="_jfzl4UAMEe2U8vhnCytY6A" value="72"/>
        <attribute defType="com.stambia.file.field.type" id="_jfzl4kAMEe2U8vhnCytY6A" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_jfzl40AMEe2U8vhnCytY6A" value="F2"/>
      </node>
      <node defType="com.stambia.file.field" id="__wyIMEAMEe2U8vhnCytY6A" name="STATE_CODE" position="78">
        <attribute defType="com.stambia.file.field.physicalName" id="__w0kcEAMEe2U8vhnCytY6A" value="C7"/>
        <attribute defType="com.stambia.file.field.type" id="__w0kcUAMEe2U8vhnCytY6A" value="String"/>
        <attribute defType="com.stambia.file.field.size" id="__w0kckAMEe2U8vhnCytY6A" value="10"/>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_IBzmYEAREe2U8vhnCytY6A" name="ref_us_states">
      <attribute defType="com.stambia.file.file.type" id="_IDdzQEAREe2U8vhnCytY6A" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_IDiEsEAREe2U8vhnCytY6A" value="UTF-8"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_IDirwEAREe2U8vhnCytY6A" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_IDjS0EAREe2U8vhnCytY6A" value="2C"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_IDj54EAREe2U8vhnCytY6A" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_IDkg8UAREe2U8vhnCytY6A" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_IDlIAEAREe2U8vhnCytY6A" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_IDlIAUAREe2U8vhnCytY6A" value="1"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_IzCPAEAREe2U8vhnCytY6A" value="REF_US_STATES.csv"/>
      <node defType="com.stambia.file.field" id="_Lg0D4EAREe2U8vhnCytY6A" name="STATE_UPPER_CASE" position="1">
        <attribute defType="com.stambia.file.field.size" id="_Lg0D4UAREe2U8vhnCytY6A" value="66"/>
        <attribute defType="com.stambia.file.field.type" id="_Lg0D4kAREe2U8vhnCytY6A" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_Lg0D40AREe2U8vhnCytY6A" value="F1"/>
      </node>
      <node defType="com.stambia.file.field" id="_Lg0D5EAREe2U8vhnCytY6A" name="STATE" position="2">
        <attribute defType="com.stambia.file.field.size" id="_Lg0D5UAREe2U8vhnCytY6A" value="64"/>
        <attribute defType="com.stambia.file.field.type" id="_Lg0D5kAREe2U8vhnCytY6A" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_Lg0D50AREe2U8vhnCytY6A" value="F2"/>
      </node>
      <node defType="com.stambia.file.field" id="_Lg0D6EAREe2U8vhnCytY6A" name="STATE_CODE" position="3">
        <attribute defType="com.stambia.file.field.size" id="_Lg0D6UAREe2U8vhnCytY6A" value="60"/>
        <attribute defType="com.stambia.file.field.type" id="_Lg0D6kAREe2U8vhnCytY6A" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_Lg0D60AREe2U8vhnCytY6A" value="F3"/>
      </node>
    </node>
    <node defType="com.stambia.file.file" id="_0OqAUEQTEe2eie-NWEkmRw" name="time">
      <attribute defType="com.stambia.file.file.type" id="_0TutkUQTEe2eie-NWEkmRw" value="DELIMITED"/>
      <attribute defType="com.stambia.file.file.charsetName" id="_0T33gEQTEe2eie-NWEkmRw" value="UTF-8"/>
      <attribute defType="com.stambia.file.file.lineSeparator" id="_0T33gUQTEe2eie-NWEkmRw" value="0D0A"/>
      <attribute defType="com.stambia.file.file.fieldSeparator" id="_0T33gkQTEe2eie-NWEkmRw" value="3B"/>
      <attribute defType="com.stambia.file.file.decimalSeparator" id="_0UBogEQTEe2eie-NWEkmRw" value="2E"/>
      <attribute defType="com.stambia.file.file.lineToSkip" id="_0UBogkQTEe2eie-NWEkmRw" value="0"/>
      <attribute defType="com.stambia.file.file.lastLineToSkip" id="_0UBog0QTEe2eie-NWEkmRw" value="0"/>
      <attribute defType="com.stambia.file.file.header" id="_0UBohEQTEe2eie-NWEkmRw" value="0"/>
      <attribute defType="com.stambia.file.file.physicalName" id="_1D_s4EQTEe2eie-NWEkmRw" value="Time.csv"/>
      <node defType="com.stambia.file.field" id="_3OcLMEQTEe2eie-NWEkmRw" name="day_date" position="1">
        <attribute defType="com.stambia.file.field.size" id="_3OcLMUQTEe2eie-NWEkmRw" value="66"/>
        <attribute defType="com.stambia.file.field.type" id="_3OcLMkQTEe2eie-NWEkmRw" value="String"/>
        <attribute defType="com.stambia.file.field.physicalName" id="_3OcLM0QTEe2eie-NWEkmRw" value="F1"/>
      </node>
    </node>
  </node>
</md:node>