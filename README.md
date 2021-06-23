# Drawbridge Motor

MakeCode package for the TomatoCube Drawbridge motor driver.


## Motor Blocks

The MakerBit board provides a motor controller that can control two bi-directional DC motors, or four one-direction motors.

### MakerBit runMotor

Sets the speed of a motor in the range of -100 to 100.

```sig
makerbit.runMotor(MakerBitMotor.A, 80)
```

### MakerBit stopMotor

Stops a motor.

```sig
makerbit.stopMotor(MakerBitMotor.A)
```

### MakerBit setMotorDirection

Sets the rotation direction of a motor. Use this function at start time to configure your motors without the need to rewire.

```sig
makerbit.setMotorRotation(MakerBitMotor.A, MakerBitMotorRotation.Backward)
```

## License

Licensed under the MIT License (MIT). See LICENSE file for more details.

## Supported targets

- for PXT/microbit
