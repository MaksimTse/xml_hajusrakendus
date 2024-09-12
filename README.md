![image](https://github.com/user-attachments/assets/d5e562f0-668d-47a5-b423-30c74884c406)

![image](https://github.com/user-attachments/assets/b414d4f2-a083-4f22-b19f-53c8b3c16f3c)

![image](https://github.com/user-attachments/assets/69cb37bd-ee53-42e9-9048-1c780de4e1ed)

![image](https://github.com/user-attachments/assets/9343972c-668b-4550-a862-a44d077bfa45)

![image](https://github.com/user-attachments/assets/e953956b-0d84-420c-87cc-0da654d7ba50)

<?xml version="1.0" encoding="utf-8"?>
<xs:schema attributeFormDefault="unqualified" elementFormDefault="qualified" xmlns:xs="http://www.w3.org/2001/XMLSchema">
	<xs:element name="Reisid">
		<xs:complexType>
			<xs:sequence>
				<xs:element maxOccurs="unbounded" name="Reisi">
					<xs:complexType>
						<xs:sequence>
							<xs:element name="Lend">
								<xs:complexType>
									<xs:sequence>
										<xs:element name="Hind" type="xs:unsignedShort" />
										<xs:element name="Valjumine">
											<xs:complexType>
												<xs:sequence>
													<xs:element name="Linn" type="xs:string" />
													<xs:element name="Aeg" type="xs:string" />
												</xs:sequence>
											</xs:complexType>
										</xs:element>
										<xs:element name="Saabumine">
											<xs:complexType>
												<xs:sequence>
													<xs:element name="Linn" type="xs:string" />
													<xs:element name="Aeg" type="xs:string" />
												</xs:sequence>
											</xs:complexType>
										</xs:element>
										<xs:element name="LennujaamaNimi" type="xs:string" />
										<xs:element name="TransportHind" type="xs:unsignedByte" />
									</xs:sequence>
								</xs:complexType>
							</xs:element>
						</xs:sequence>
						<xs:attribute name="reisi_id" type="xs:unsignedByte" use="required" />
					</xs:complexType>
				</xs:element>
			</xs:sequence>
		</xs:complexType>
	</xs:element>
</xs:schema>
