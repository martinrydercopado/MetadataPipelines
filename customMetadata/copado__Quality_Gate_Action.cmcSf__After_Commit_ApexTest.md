<?xml version="1.0" encoding="UTF-8"?>
<CustomMetadata xmlns="http://soap.sforce.com/2006/04/metadata" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
    <label>After Commit ApexTest</label>
    <protected>false</protected>
    <values>
        <field>copado__Action__c</field>
        <value xsi:type="xsd:string">Commit</value>
    </values>
    <values>
        <field>copado__Details__c</field>
        <value xsi:type="xsd:string">If it fails, any promotion containing this commit will be blocked.</value>
    </values>
    <values>
        <field>copado__Environment_Info_Message__c</field>
        <value xsi:type="xsd:string">Copado will create as many quality gates as needed based on your selection. They will share the same configuration, but you will be able to edit each of them individually.</value>
    </values>
    <values>
        <field>copado__Execution_Sequence_Icon__c</field>
        <value xsi:nil="true"/>
    </values>
    <values>
        <field>copado__Info_Message__c</field>
        <value xsi:type="xsd:string">The quality gate will be executed in the selected environment.</value>
    </values>
    <values>
        <field>copado__Is_Default__c</field>
        <value xsi:type="xsd:boolean">true</value>
    </values>
    <values>
        <field>copado__Select_Environment_Message__c</field>
        <value xsi:type="xsd:string">Select the environments where changes will be implemented (e.g. Development or Hotfix environments)</value>
    </values>
    <values>
        <field>copado__Sequence__c</field>
        <value xsi:type="xsd:string">After</value>
    </values>
    <values>
        <field>copado__Test_Tool__c</field>
        <value xsi:type="xsd:string">cmcSf__ApexTests</value>
    </values>
    <values>
        <field>copado__Tool_Sequence_Status__c</field>
        <value xsi:type="xsd:string">Block</value>
    </values>
</CustomMetadata>
