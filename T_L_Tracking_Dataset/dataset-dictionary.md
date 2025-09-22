| **Coluna**                           | **Descrição**                                                         |
| ------------------------------------ | --------------------------------------------------------------------- |
| `GpsProvider`                        | Provedor de rastreamento do veículo (ex.: CONSENT TRACK, VAMOSYS).    |
| `BookingID`                          | Identificador único da entrega/viagem.                                |
| `Market/Regular`                     | Tipo de operação logística (Market ou Regular).                       |
| `BookingID_Date`                     | Data e hora do agendamento da entrega.                                |
| `vehicle_no`                         | Número da placa/código do veículo utilizado.                          |
| `Origin_Location`                    | Local de origem da carga (nome do hub, fábrica ou armazém).           |
| `Destination_Location`               | Local de destino da carga.                                            |
| `Org_lat_lon`                        | Latitude e longitude do ponto de origem.                              |
| `Des_lat_lon`                        | Latitude e longitude do destino.                                      |
| `Data_Ping_time`                     | Data/hora em que os dados de localização foram registrados.           |
| `Planned_ETA`                        | Tempo estimado de chegada planejado (Estimated Time of Arrival).      |
| `Current_Location`                   | Localização atual do veículo.                                         |
| `DestinationLocation`                | Local de destino formatado/agrupado.                                  |
| `actual_eta`                         | Tempo estimado de chegada real, considerando as condições do trajeto. |
| `Curr_lat`                           | Latitude atual do veículo.                                            |
| `Curr_lon`                           | Longitude atual do veículo.                                           |
| `ontime`                             | Indicador de pontualidade (se chegou dentro do prazo).                |
| `delay`                              | Atraso registrado na entrega (em horas/minutos).                      |
| `OriginLocation_Code`                | Código interno associado ao local de origem.                          |
| `DestinationLocation_Code`           | Código interno associado ao destino.                                  |
| `trip_start_date`                    | Data de início da viagem.                                             |
| `trip_end_date`                      | Data de término da viagem.                                            |
| `TRANSPORTATION_DISTANCE_IN_KM`      | Distância percorrida na viagem (em km).                               |
| `vehicleType`                        | Tipo de veículo utilizado (ex.: 32 FT Multi-Axle 14MT - HCV).         |
| `Minimum_kms_to_be_covered_in_a_day` | Distância mínima planejada por dia (pode estar em branco).            |
| `Driver_Name`                        | Nome do motorista responsável.                                        |
| `Driver_MobileNo`                    | Número de telefone do motorista.                                      |
| `customerID`                         | Código de identificação do cliente.                                   |
| `customerNameCode`                   | Nome/código do cliente associado à entrega.                           |
| `supplierID`                         | Código de identificação do fornecedor.                                |
| `supplierNameCode`                   | Nome/código do fornecedor associado à entrega.                        |
| `Material Shipped`                   | Material transportado (ex.: peças automotivas, etc.).                 |


# LINK: 
## [Dataset](https://www.kaggle.com/datasets/nicolemachado/transportation-and-logistics-tracking-dataset)